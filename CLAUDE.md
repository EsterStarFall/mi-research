# MI Research — 카카오페이 전사 Market Intelligence 하네스

## 프로젝트 목적

카카오페이 전사 전략 조직에서 내년도 사업계획 수립을 지원하기 위해, 아래 11개 사업 영역에 대한
외부환경(시장/규제/경쟁/해외) 리서치를 수행하고, 전사 사업/서비스 부서에 공유할 트렌드·인사이트
리포트를 만든다.

결과물은 비개발 직군 동료들이 그대로 읽고 신뢰할 수 있어야 한다. 전사 대상으로 나가는 리포트이므로
**모든 수치는 반드시 원본 출처 링크가 각주로 달려 있어야 하고, 사람이 검수할 수 있는 구조**를 갖춰야 한다.

## 조사 대상 (11개 도메인 × 4개 분석축)

도메인:
1. 결제 (payments)
2. 대출 (lending)
3. 보험 (insurance)
4. 투자&증권 (investment-securities)
5. 카드중개 (card-brokerage)
6. 통신중개 (telecom-brokerage)
7. 광고 (advertising)
8. 데이터 기반 비즈니스 (data-business)
9. 머니&송금 (money-remittance)
10. 그로스 (growth)
11. 기술 (technology)

각 도메인마다 아래 4개 축을 모두 조사한다:
- 시장현황 (시장 규모, 성장률, 주요 지표)
- 규제 변화 (최근/예정 법·제도 변화)
- 경쟁 동향 (국내 경쟁사 움직임)
- 해외 시장 및 경쟁 동향 (해외 유사 시장/플레이어 사례)

진행 상황은 [research-tracker.md](research-tracker.md)에서 도메인 × 축 매트릭스로 관리한다.

## 할루시네이션 방지 원칙 (반드시 준수)

전사 대상 리포트이므로 **숫자를 지어내는 것은 절대 금지**한다. 이를 구조적으로 막기 위해 아래
파이프라인을 강제한다.

1. **리서치와 작성을 분리한다.**
   - `market-researcher` 서브에이전트만 실제 웹 조사를 수행하고, 찾은 모든 사실/수치를
     `evidence/<domain>.md`에 근거(출처 URL, 원문 발췌, 확인일)와 함께 기록한다.
   - `report-writer` 서브에이전트는 **직접 웹 검색을 하지 않고**, 오직 `evidence/`와
     `data/output/`에 이미 기록된 내용만 사용해 리포트를 작성한다.
   - `evidence/`에 근거가 없는 숫자는 리포트에 절대 넣지 않는다. 필요한데 근거가 없으면
     "확인 필요"로 표시하고 market-researcher에게 추가 조사를 요청한다.

2. **모든 수치에는 각주로 원본 링크를 단다.**
   - 리포트 본문에 숫자가 등장하면 예외 없이 각주(`[^n]`)를 달고, 각주에는 실제 출처 URL을
     포함한다. 각주만 보고도 사람이 원문을 클릭해서 검증할 수 있어야 한다.
   - 포맷은 [templates/report-template.md](templates/report-template.md) 참고.

3. **검수는 작성자와 분리된 에이전트가 한다.**
   - `fact-checker` 서브에이전트가 초안의 모든 숫자를 훑어, 각주-출처 링크-evidence 기록이
     실제로 일치하는지 대조한다.
   - 불일치하거나 근거가 부실한 항목은 `review/<domain>-checklist.md`에 플래그로 남기고,
     사람이 최종 검수하기 전까지 "완료" 상태로 표시하지 않는다.

4. **모르면 모른다고 한다.**
   - 검색으로 확인되지 않는 수치는 그럴듯하게 추정해서 채우지 않는다. "확인 필요" 또는
     "출처 없음"으로 명시한다.

5. **검증 실패는 사람에게 던지고 끝나지 않는다 — 재조사 루프를 강제로 돈다.**
   - fact-checker가 ❌를 발견하면 먼저 유형을 나눈다.
     - **A형 (근거 없음)**: evidence에 아예 없는 숫자를 리포트에 썼다 — 할루시네이션 의심.
     - **B형 (오인용)**: 각주 URL은 있지만 evidence 원문이 실제로 그 숫자를 뒷받침하지 않는다.
     - **C형 (단순 표기 누락)**: 값 자체는 evidence에 있는데 각주만 안 달렸다.
   - **C형은 재조사 없이** report-writer가 각주만 보완하면 끝난다.
   - **A형/B형은 자동으로 재조사 루프에 들어간다** (사람이 매번 "재조사해줘"라고 시키지
     않아도 된다):
     1. fact-checker가 `review/<domain>-checklist.md`에 해당 항목을 "재조사 1차 요청"으로
        남긴다.
     2. market-researcher가 그 항목만 타겟으로 다시 조사한다 — ① 원 출처를 다시 찾거나,
        ② 안 되면 대체/유사 지표로 논리를 보완해 새로운 data point를 잡거나, ③ 그래도
        안 되면 "확인 불가 (시도한 방법 기록)"로 evidence에 남긴다.
     3. report-writer가 그 결과를 리포트에 반영한다 (숫자·각주 갱신 또는 "확인 필요"로 대체).
     4. fact-checker가 그 항목만 다시 검수한다.
     5. 그래도 실패하면 2차까지 같은 절차를 반복한다.
   - **최대 2회 재조사까지만 자동으로 돈다.** 2회 재조사 후에도 확인이 안 되면 루프를
     멈추고, report-writer는 그 숫자를 **리포트 본문에서 반드시 제거**하거나 "확인 필요"
     문구로 대체해야 한다 (애매하게 남겨두고 넘어가지 않는다). 이 상태는
     `research-tracker.md`에 "사람 확인 필요"로 표시하고 사람에게 에스컬레이션한다.
   - 모든 라운드(1차/2차 재조사 요청과 결과)는 `review/<domain>-checklist.md`에 남겨,
     나중에 누구든 "이 숫자가 왜 이렇게 됐는지" 이력을 추적할 수 있어야 한다.

## 서브에이전트 구성

- [.claude/agents/market-researcher.md](.claude/agents/market-researcher.md) — 도메인별 웹 리서치, evidence 기록
- [.claude/agents/data-manager.md](.claude/agents/data-manager.md) — 정형 데이터 수집/계산(크롤링, 집계), `data/output/`에 출처와 함께 저장
- [.claude/agents/report-writer.md](.claude/agents/report-writer.md) — evidence만 사용해 리포트 초안 작성
- [.claude/agents/fact-checker.md](.claude/agents/fact-checker.md) — 초안 검수, 각주-출처 대조

## 작업 흐름

1. 도메인 하나를 선택 → `market-researcher`에게 4개 축 조사를 요청 → `evidence/<domain>.md`에 근거 축적
2. 정형 지표(시장 규모 등 계산이 필요한 값)는 `data-manager`가 스크립트로 수집/계산 → `data/output/`에 저장
3. 충분히 근거가 쌓이면 `report-writer`가 `reports/<domain>.md` 초안 작성 (각주 필수)
4. `fact-checker`가 초안 검수 → `review/<domain>-checklist.md` 생성
5. ❌ 항목(A형/B형) 발견 시 → market-researcher 타겟 재조사 → report-writer 반영 →
   fact-checker 재검수. 최대 2회까지 자동 반복 (위 "할루시네이션 방지 원칙 5." 참고)
6. 2회 재조사 후에도 미해결이면 report-writer가 숫자를 제거/대체하고 사람에게 에스컬레이션
7. 사람이 checklist를 보고 최종 확인 → 완료된 리포트만 전사 공유

## 폴더 구조

```
mi-research/
├── CLAUDE.md                  # 이 파일 — 프로젝트 전체 규칙
├── README.md                  # 비개발 팀원용 안내
├── research-tracker.md        # 11개 도메인 × 4개 분석축 진행 매트릭스
├── .claude/agents/            # 서브에이전트 정의 (자연어 md)
├── evidence/                  # 도메인별 리서치 근거 원장 (source of truth)
├── data/scripts/              # data-manager의 크롤링/계산 스크립트
├── data/output/                # 위 스크립트의 산출 데이터 + 출처 메타데이터
├── reports/                    # 최종 리포트 (각주로 출처 링크 포함)
├── review/                     # fact-checker의 검수 체크리스트
└── templates/                  # evidence/report 작성 템플릿
```

## 참고

이 레포는 여러 PC에서 동일하게 동작하도록 코드/의존성 없이 자연어(마크다운) 기반으로
구성되어 있다. `.claude/agents/`만 있으면 어느 PC에서 `claude` CLI로 clone해서 그대로
같은 방식으로 작업을 이어갈 수 있다.
