# Evidence — 오프라인 결제 (Offline Payments)

> 방법론: [../scope.md](../scope.md) 참고. 2026년 상반기(2026-01-01~2026-06-30) 중 처음
> 공개/출시/화제화된 사례만 기록. 정량 지표가 아닌 "새로 나타난 트렌디한 컨텐츠/사례" 카탈로그용
> 근거 원장.

> **⚠ 2026-08-14 기준 재조사 안내**: 아래 "## 해외 (구 버전)"·"## 국내 (구 버전)" 섹션은
> 개정 전 기준(화제성·시사점 뚜렷함)으로 조사된 내용이다. 사용자 피드백에 따라 scope.md의
> "트렌디하다의 판단 기준"이 "참신성/실험성 최우선, 기업 규모 무관, 성공사례 불필요"로
> 개정되었고, 구 버전 항목 대부분(카카오페이 톱4 선언, 네이버페이-파리바게뜨 제휴, 수수료
> 면제 프로모션, Ingenico/Verifone/FAB 등 대형 벤더 사례)은 새 기준에 부합하지 않아 카탈로그
> 채택 대상에서 제외한다. 삭제하지 않고 감사 추적용으로 보존만 한다. 새 기준에 따른 조사는
> 아래 "## 해외 (신규 기준)"·"## 국내 (신규 기준)" 섹션에 별도로 기록한다.

## 해외 (구 버전 — 2026-08-14 이전 기준, 카탈로그 채택 제외)

### 1. Ingenico × WalletConnect Pay — 매장 결제 단말에서 스테이블코인 결제 지원

- **유형 태그**: 신규 서비스·기능 / 파트너십·비즈니스모델
- **무엇이 새로운가**: 전 세계 매장에 깔린 안드로이드 기반 Ingenico POS 단말(AXIUM 등)에서
  하드웨어 교체 없이 소프트웨어 업데이트만으로 USDC·EURC·USDT 등 스테이블코인 결제를 받을 수
  있게 됐다. WalletConnect 프로토콜을 통해 700개 이상의 크립토 지갑과 연동되며, 소매·숙박·
  주유소·주차·자판기 등 대면 결제 전 영역을 겨냥한 첫 대규모 상용 스테이블코인 오프라인 결제
  인프라 사례다.
- **발생 시점**: 2026년 1월
- **원문 발췌**: "Ingenico announced a partnership with WalletConnect Pay in January 2026 to
  enable stablecoin payments directly at checkout... The integration allows millions of
  Ingenico's Android-based payment terminals globally to accept five major stablecoins including
  USDC, EURC and USDT at point of sale. Customers can pay using any of more than 700 compatible
  crypto wallets through the WalletConnect protocol... The solution is designed for use in a wide
  range of merchant settings, including retail, hospitality, transportation, fuel, parking,
  vending, and self-service... the integration does not require additional hardware upgrades or
  direct exposure to digital asset custody."
- **출처명**: Ledger Insights / American Banker (PaymentsSource) / Ingenico Newsroom 보도자료
  종합 (WebSearch 결과 요약)
- **출처 URL**: https://www.ledgerinsights.com/ingenico-enables-stablecoin-payments-at-physical-point-of-sale/ ,
  https://ingenico.com/us-en/newsroom/press-releases/ingenico-launches-digital-currency-solution-enabling-stablecoin-payments ,
  https://www.prnewswire.com/news-releases/ingenico-launches-digital-currency-solution-enabling-stablecoin-payments-at-physical-checkouts-in-partnership-with-walletconnect-pay-302661216.html
- **확인일**: 2026-08-14
- **재조사 1차 (B형, 경미 — "AXIUM" 모델명)**: 원 출처 3건(ledgerinsights·ingenico·prnewswire)을
  재확인했으나 어디에도 "AXIUM" 모델명이 등장하지 않음(모두 "Android-based payment terminals"로만
  표현). 대체 출처로 Ingenico의 별도 보도자료를 새로 확인함 — "Ingenico Launches Next-Generation
  AXIUM Payment Device Family and Ingenico 360 Unified Cloud Platform"(2026-02-10 발표, PR
  Newswire): "Android 14 foundation" / "Support for digital identity, stablecoin acceptance,
  loyalty, and digital receipts" — AXIUM이 실제 Ingenico의 안드로이드 기반·스테이블코인 지원
  단말기 제품군명임을 확인. 다만 이는 WalletConnect Pay 파트너십(2026년 1월) 발표와는 별개의
  2026년 2월 10일 발표 자료이므로, "1월 파트너십 당시 AXIUM 단말에서 바로 지원됐다"는 인과관계
  까지는 원문으로 직접 뒷받침되지 않음. 카탈로그 표기 시 "AXIUM 등"이라는 예시 문구는 유지하되
  이 caveat을 참고할 것. 출처명: PR Newswire(Ingenico) / 출처 URL:
  https://www.prnewswire.com/news-releases/ingenico-launches-next-generation-axium-payment-device-family-and-ingenico-360-unified-cloud-platform-302683177.html
  / 확인일: 2026-08-14
- **카카오페이 시사점 메모**: 국내는 아직 스테이블코인 오프라인 결제 인프라가 초기 단계다.
  카드리더기/키오스크 벤더가 소프트웨어 업데이트만으로 스테이블코인 수납을 지원하는 모델은,
  향후 원화 스테이블코인 논의가 본격화될 경우 카카오페이 가맹점 단말 전략에 참고할 만한
  "하드웨어 불변, 소프트웨어만 확장" 구조다.

### 2. Verifone — Victa SoftPOS Mobile / Tablet 신제품 출시 (NRF 2026)

- **유형 태그**: 신규 서비스·기능
- **무엇이 새로운가**: 전용 결제 단말 없이 상용 모바일 기기·태블릿에서 바로 비접촉 결제를 받는
  SoftPOS 제품군을 확장했다. Shopify POS 연동, Bilt·Aevi 등과의 신규 제휴도 함께 발표되어
  소상공인·이동형 매장(온사이트 서비스 등)의 결제 접점을 하드웨어 구매 없이 넓히는 흐름을
  보여준다.
- **발생 시점**: 2026년 1월 (1월 8~9일 발표, NRF Big Show 2026 — 2026년 1월 11~13일 뉴욕)
- **원문 발췌**: "Victa SoftPOS Mobile supports on-the-go use with integrated contactless
  payments, while Victa SoftPOS Tablet offers a larger touchscreen to support customer-facing and
  operational tasks... Verifone now supports Shopify Point of Sale with select Victa devices, as
  well as new alliances with Bilt and Aevi." / 담당 임원 인용: "By continuing to grow our Victa
  portfolio of offerings, we're giving merchants and solution providers more ways to deliver
  consistent, secure payment experiences—whether at the counter or on the move." — Prasanna
  Narayan, EVP·Head of Product, Verifone
- **출처명**: GlobeNewswire (Verifone 보도자료), Verifone Knowledge Hub
- **출처 URL**: https://www.globenewswire.com/news-release/2026/01/08/3215605/0/en/Verifone-Enters-2026-with-Expanded-Victa-Line-and-Broadened-Partner-Ecosystem.html ,
  https://www.verifone.com/resources/verifone-announces-expanded-victa-line-broadened-partner-ecosystem
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: SoftPOS(탭투페이 소프트웨어화)가 이제 "신기능"이 아니라 벤더
  제품 라인의 기본 옵션으로 자리잡는 중. 카카오페이 오프라인 결제 조직의 가맹점 확장 전략에서
  전용 단말 배포 없이 소상공인 온보딩 속도를 높이는 카드로 참고 가능.

### 3. Tapster — 세계 최초 비스포크(맞춤형) 시그넷 페이먼트 링 출시

- **유형 태그**: 신규 서비스·기능 (UX/인터페이스 패턴 — 웨어러블 결제 폼팩터)
- **무엇이 새로운가**: 스웨덴 스타트업 Tapster가 배터리·충전·화면이 전혀 없는 완전 수동형
  NFC 결제 반지를, 전통 시그넷 링(인장 반지) 디자인과 결합해 "개인 맞춤 제작(bespoke)"
  형태로 출시했다. 접촉식 결제가 가능한 모든 매장에서 카드/폰 없이 반지만으로 대면 결제가
  가능하다.
- **발생 시점**: 2026년 1월 (1월 7일)
- **원문 발췌**: "Payments should be effortless, invisible, and always available. With the launch
  of the world's first bespoke payment signet ring, we're bringing together timeless design and
  passive NFC technology to show what the future of payments can look like — secure, elegant, and
  always on." — Ludvig Scheja, CPO and Co-Founder of Tapster. (제품: "a fully passive wearable...
  requiring no batteries, charging, or screens, functioning as a secure payment device anywhere
  contactless payments are accepted.") / [재조사 1차, B형 해소 — 스웨덴 스타트업] 원문 재확인
  결과 다음 문장을 확인: "Tapster, a Swedish innovator in NFC wearables" 및 회사 소개 섹션:
  "Tapster is a Swedish technology company specializing in NFC wearables" (동일 pressat.co.uk
  URL, 처음 조사 시 누락됐던 문장을 재확인으로 발견. 확인일 2026-08-14) / [재조사 1차, D형
  해소 — 발생일 2026-01-07] 원문 상단 배포일 표기: "News provided by TAPSTER on Wednesday 7th
  Jan 2026" 및 하단: "Press release distributed by Pressat on behalf of TAPSTER, on Wednesday
  7 January, 2026" (동일 URL. 확인일 2026-08-14)
- **출처명**: Pressat (보도자료 배포)
- **출처 URL**: https://pressat.co.uk/releases/tapster-launches-the-worlds-first-bespoke-payment-signet-ring-advancing-the-future-of-payments-0a88c327341a3ffa06328b61596b9706/
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: 웨어러블 결제 폼팩터가 "기능"에서 "패션 아이템"으로 이동하는
  신호. 오프라인 결제 UX를 카드/폰 이후의 접점(반지·팔찌 등)으로 확장하려는 시도가 스타트업
  단위에서 이미 시작됨 — 국내는 아직 초기 단계라 브랜드 파트너십 관점에서 모니터링 가치 있음.

### 4. First Abu Dhabi Bank × Mastercard × Tappy Technologies × Thales — 피트니스 결제 링 출시

- **유형 태그**: 파트너십·비즈니스모델 (신규 서비스·기능 겸함)
- **무엇이 새로운가**: 은행(FAB)·카드사(Mastercard)·웨어러블 결제 스타트업(Tappy)·보안칩
  기업(Thales) 4자가 협업해, 피트니스 트래킹 기능과 탭투페이 결제 기능을 한 제품에 결합한
  웨어러블 링을 상용 출시했다. 은행 채널을 통해 FAB 발급 Mastercard 체크/신용카드를 토큰화해
  반지에 프로비저닝하는 구조로, 통신사·카드사·제조사가 아닌 "은행 주도"의 웨어러블 결제
  파트너십이라는 점이 특징이다.
- **발생 시점**: 2026년 1월 (1월 18일), UAE
- **원문 발췌**: "This incredible launch with FAB represents a defining moment in wearable
  payments. We are proud to collaborate on this pioneering fitness and payment ring." — Suboor
  Ahmed, Co-Founder & COO, Tappy Technologies. "Technology is at the heart of the UAE's national
  vision, and this launch highlights how partnerships can bring innovation directly into people's
  lives." — Abdelhafid Mordi, CEO of Thales UAE. (제품 설명: 사용자는 FAB Mastercard 체크/신용
  카드를 토큰화해 탭투페이 거래에 사용, 다양한 색상·사이즈로 은행 채널을 통해 제공)
- **출처명**: Tappy Technologies 보도자료
- **출처 URL**: https://tappytech.com/news/the-fab-fitness-payment-ring-secure-payments-meet-innovative-wearable-technology-with-mastercard-tappy-and-thales/
- **확인일**: 2026-08-14
- **재조사 1차 (D형 해소 — 발생일 2026-01-18)**: 원 출처(tappytech.com) 기사 본문 최상단
  dateline을 재확인한 결과 다음 문장을 직접 확인: "Abu Dhabi – 18 January 2026" (동일 URL,
  처음 조사 시 누락됐던 dateline을 재확인으로 발견. 확인일 2026-08-14)
- **카카오페이 시사점 메모**: 카드사·발급은행이 직접 웨어러블 결제 폼팩터를 자사 카드 채널
  확장 수단으로 쓰는 사례. 카드중개 조직이 제휴 카드사와 함께 검토할 만한 "카드 발급 이후
  접점 확장" 파트너십 모델.

### 5. 중국-인도네시아 국경간 QR결제 연동 — Alipay+ × UnionPay International × QRIS

- **유형 태그**: 파트너십·비즈니스모델
- **무엇이 새로운가**: 인도네시아 중앙은행(Bank Indonesia)과 중국 인민은행(PBOC) 주도로,
  인도네시아 전역 4,000만 개 이상 QRIS 가맹점(대부분 영세 소상공인)에서 중국 여행객이 자국
  Alipay·UnionPay 앱으로 결제할 수 있게 됐다. 반대로 QRIS 지원 지갑 사용자는 중국 내
  8,000만 개 이상의 Alipay·UnionPay QR코드에서 결제 가능. 가맹점은 기존 QRIS 코드 그대로
  사용하면 되고 별도 하드웨어가 필요 없다는 점이 핵심.
- **발생 시점**: 2026년 5월 (5월 7일)
- **원문 발췌**: "the China-Indonesia cross-border QR payment linkage was launched between
  Indonesia's QRIS and China's leading payment ecosystems, enabled by Alipay+ and UnionPay
  International... connects over 40 million QRIS merchants in Indonesia... QRIS-supported wallets
  can access 'over 80 million Alipay and UnionPay QR codes within China'... an existing merchant
  QRIS code is all that's needed to accept payments from Chinese travellers." 관계자 인용:
  "Interoperability is the foundation of the next generation of cross-border payments." — Michael
  Guo, Alipay+ General Manager for SEA, South Asia and ANZ.
- **출처명**: The Asian Banker (보도자료 기반 기사)
- **출처 URL**: https://www.theasianbanker.com/press-releases/china-indonesia-qr-payment-link-connects-40-million-merchants-to-chinese-travellers
- **확인일**: 2026-08-14
- **재조사 1차 (D형 해소 — 발생일 2026-05-07)**: 원 출처(theasianbanker.com) 기사 본문을
  재확인한 결과 dateline에서 직접 확인: "SINGAPORE, 7 May 2026 —" (동일 URL, 처음 조사 시
  누락됐던 dateline을 재확인으로 발견). 추가로 대체 출처 TNGlobal(technode.global) 기사도
  동일 사실을 2026-05-07 발행 기사에서 "In a statement on Thursday, Alipay+ said..."로 보도
  (2026년 5월 7일은 실제 목요일과 일치해 교차검증됨). 확인일: 2026-08-14
- **카카오페이 시사점 메모**: 동남아 QR 인터오퍼러빌리티가 "역내 국가간"을 넘어 중국이라는
  대형 아웃바운드 관광 시장과 연결되는 단계로 진입. 카카오페이가 참여 중인 국경간 QR 결제
  협력(예: 국내-동남아)에서 벤치마크할 만한 "가맹점 하드웨어 불변 + 지갑단 게이트웨이 연동"
  구조. 다만 이 사례는 한국이 아닌 중국-인도네시아 양자 간 연동이라 국내 시장과 직접 겹치지
  않음.

### 6. ECB 디지털 유로 파일럿 — 오프라인 근접결제(NFC)·SoftPOS 매장결제 테스트 범위 확정

- **유형 태그**: 규제·정책발 신규 시도
- **무엇이 새로운가**: 유럽중앙은행이 디지털 유로 파일럿에 참여할 결제서비스제공자(PSP) 공모를
  개시하면서, 테스트 범위에 "오프라인 근접결제(NFC)"와 "매장 SoftPOS 결제"를 명시적 유스케이스로
  포함시켰다. 오프라인 결제는 인터넷 연결 없이 지급인-수취인 간에만 거래 정보가 남아 현금과
  유사한 프라이버시를 제공하는 것이 특징. Deutsche Bank, UniCredit, Revolut, Adyen, Stripe 등
  36개 결제사업자가 공모에 선정됐다(2026년 7월 14일 발표 — 참고: 이 선정 발표 자체는 2026년
  하반기이나, 공모 개시와 오프라인 NFC/SoftPOS 테스트 범위 확정은 2026년 상반기(3월)에 이뤄짐).
- **발생 시점**: 2026년 3월 (3월 5일 공모 개시, 5월 14일 마감)
- **원문 발췌**: "Staff of participating central banks will have the opportunity to make digital
  euro payments from person to person (both online and offline), and from person to business (both
  at the physical point of sale and in e-commerce, including mobile commerce)." (ECB, 2026-03-05
  보도자료) — 관련 보도: "The pilot is designed to test four primary use cases: online
  person-to-person payments, offline proximity payments via NFC, in-store payments using SoftPOS
  solutions, and e-commerce transactions."
- **출처명**: European Central Bank 공식 보도자료 / Euronews
- **출처 URL**: https://www.ecb.europa.eu/press/intro/news/html/ecb.mipnews260305.en.html ,
  https://www.euronews.com/business/2026/07/14/ecb-selects-36-payment-providers-for-digital-euro-pilot-as-the-project-moves-ahead
- **확인일**: 2026-08-14
- **비고**: PSP 최종 선정(36개사) 발표는 2026-07-14로 상반기 이후이므로, 본 항목은 "오프라인
  NFC/SoftPOS 테스트 범위가 상반기 중 공식 확정·공모됐다"는 사실만을 상반기 트렌드로 채택함.
  실제 파일럿 가동은 2027년 하반기 예정.
- **재조사 1차 (B형 해소 — "2027년 하반기 파일럿")**: 원 출처 2건을 재확인한 결과 모두 원문에
  직접 명시되어 있음을 재확인. ECB 보도자료(2026-03-05, ecb.mipnews260305): "The pilot, set to
  run for a duration of 12 months, will take place during the second half of 2027." / Euronews
  (2026-07-14): "a large-scale pilot programme beginning in the second half of 2027" — 처음
  검수 시 발췌 목록에 이 문장이 누락되어 있었으나, 원문 자체에는 존재함을 재확인. 확인일:
  2026-08-14
- **재조사 1차 (B형 — "인터넷 연결 없이... 현금과 유사한 프라이버시")**: 원 출처 2건
  (ECB 2026-03-05 보도자료, Euronews 2026-07-14 기사)을 재확인했으나 두 기사 모두 프라이버시·
  인터넷 연결 관련 서술이 없음을 확인(파일럿 참여기관·일정 위주 서술). 대체 출처로 ECB의 디지털
  유로 프라이버시 전용 설명 페이지를 새로 찾아 확인함 — "This functionality would combine the
  convenience of digital payments with cash-like privacy levels, without the need for an internet
  connection." / "The details of your offline digital euro payments would only be known to you
  and the recipient." 원 주장(오프라인 결제는 인터넷 연결 없이 지급인-수취인 간에만 거래정보가
  남아 현금과 유사한 프라이버시)과 정확히 부합. 출처명: European Central Bank — "Digital euro
  and privacy" / 출처 URL:
  https://www.ecb.europa.eu/euro/digital_euro/features/privacy/html/index.en.html / 확인일:
  2026-08-14
- **카카오페이 시사점 메모**: CBDC 오프라인 결제가 유럽에서도 "탭투페이/SoftPOS 매장결제"를
  명시적 테스트 축으로 삼는 점에 주목. 국내 한국은행 CBDC 논의에서도 오프라인 결제 시나리오가
  포함될 경우 가맹점 단말 연동 요구사항을 가늠할 선행 사례.

### 7. Mastercard — Agent Pay for Machines (AP4M) 출시: AI 에이전트·사물간 자동결제, 자판기·주차 등 오프라인 기기 포함

- **유형 태그**: 신규 서비스·기능 / 파트너십·비즈니스모델
- **무엇이 새로운가**: AI 에이전트와 연결기기(machine)가 사람 개입 없이 초소액(1센트 미만)
  결제까지 자동으로 주고받을 수 있는 결제 프로토콜을 출시했다. 카드·은행계좌·스테이블코인
  정산을 모두 지원하며, Stripe·Adyen·Coinbase·Cloudflare 등 30개 이상 파트너가 참여. 자판기·
  주차·주유 등 대면·오프라인 기기(machine-to-machine) 결제 시나리오를 명시적으로 겨냥한 점이
  기존 온라인 중심 에이전틱 커머스(Visa Intelligent Commerce, Mastercard Agent Pay)와
  차별점이다.
- **발생 시점**: 2026년 6월 (6월 10일)
- **원문 발췌**: "Mastercard introduced Agent Pay for Machines on June 10, a service that lets AI
  agents and connected systems pay one another automatically across its global network, with some
  payments as small as fractions of a cent... AP4M allows for permissioned, orchestrated, and
  settled transactions at machine speed across Mastercard's global network... It supports cards,
  bank accounts, and stablecoins... More than 30 partners signed on, including Stripe, Adyen,
  Coinbase, Cloudflare, OKX, Ripple, Polygon, and Solana."
- **출처명**: Fortune / Mastercard 공식 보도자료(투자자 뉴스)
- **출처 URL**: https://fortune.com/2026/06/10/mastercard-ai-payments-protocol-launch-agentic-finance/ ,
  https://www.mastercard.com/global/en/news-and-trends/press/2026/june/mastercard-launches-agent-pay-for-machines.html
- **확인일**: 2026-08-14
- **재조사 1차 (B형, 중요 — "자판기·주차·주유 등 대면·오프라인 기기 결제 시나리오를 명시적으로
  겨냥")**: 원 출처(fortune.com)를 재확인했으나 vending/parking/fuel 관련 구체 유스케이스가
  없음을 재확인(파일럿 서술은 "꽃가게 웹사이트" 같은 온라인 시나리오 위주). mastercard.com
  공식 페이지는 재접속 시도 시 403 오류로 접근 불가(2회 시도). 대체 출처로 Yahoo Finance,
  usethebitcoin.com 등을 추가 검색해 다음 문장을 확인함 — "A smart car could automatically pay
  for charging at stations, parking, or tolls on roads as needed." (usethebitcoin.com,
  2026-06-10 전후 보도) — **주의: 이 문장은 "충전소(charging stations)·주차(parking)·
  톨게이트(tolls)"를 명시하나, 카탈로그가 주장한 "자판기(vending)·주유(fuel)"라는 정확한
  단어와는 일치하지 않음.** "충전소"는 "주유"와 유사한 개념으로 볼 여지가 있으나 "자판기"에
  대응하는 언급은 어떤 출처에서도 확인되지 않음. → **부분 해소**: "오프라인·기기 결제
  시나리오를 명시적으로 겨냥했다"는 전체 취지는 대체 출처로 뒷받침되나, "자판기·주차·주유"라는
  구체 나열은 원문과 정확히 일치하지 않으므로 report-writer는 이 구체 나열 대신 "주차·충전소·
  통행료(톨) 등 기기 결제 시나리오"로 표현을 수정하거나 "자판기·주유"를 삭제할 것을 권고.
  다만 이 항목이 "오프라인 결제" 세그먼트에 속하는지 자체는, AI 에이전트가 사람 개입 없이
  물리적 기기(자동차·충전소·주차장·톨게이트)에서 결제를 수행한다는 점에서 대면·비대면 경계에
  걸쳐 있으나 완전히 온라인 전자상거래로 보기는 어려워 세그먼트 포함은 유지 가능하다고 판단됨.
  출처명: usethebitcoin.com / 출처 URL: https://usethebitcoin.com/news/mastercard-agent-pay-crypto/
  / 확인일: 2026-08-14
- **카카오페이 시사점 메모**: "오프라인 결제 = 사람이 매장에서 결제"라는 전제 자체가 흔들리는
  신호. 자판기·주차·키오스크 등 무인 오프라인 접점이 향후 AI 에이전트/사물 간 자동결제로
  전환될 가능성 — 카카오페이 오프라인 가맹점 인프라(무인매장·자판기 제휴처 등)에 중장기적으로
  영향권.

### 8. 중국 e-CNY(디지털위안화) — 예금형 화폐로 전환하는 신규 관리체계 시행 (오프라인 결제 확대 배경)

- **유형 태그**: 규제·정책발 신규 시도
- **무엇이 새로운가**: 중국인민은행이 e-CNY를 "현금성 지급수단"에서 "디지털 예금화폐"로
  격상시키는 신규 관리체계를 시행했다. 지갑 잔액에 예금 이자를 지급하고 예금자보호 대상에
  포함시키는 등 제도적 지위를 강화한 것으로, e-CNY의 핵심 차별점인 오프라인 NFC 결제(인터넷
  연결 없이 SIM·하드웨어 지갑으로 매장 탭 결제 가능)의 제도적 기반을 넓히는 조치로 해석된다.
  다만 이번 상반기 발표 내용 자체는 오프라인 결제 "기능"의 신규 출시가 아니라 그 기반이 되는
  화폐적 지위·이자 지급 규제 변화임에 유의.
- **발생 시점**: 2026년 1월 (1월 1일 시행, 발표는 2025년 12월 29~30일)
- **원문 발췌**: "an upgraded framework for digital yuan management will take effect on Jan. 1,
  2026"... 시스템은 e-CNY를 "beyond a cash-like instrument toward a form of digital deposit
  money"로 전환시키며, "Commercial banks will be required to pay interest on digital yuan wallet
  balances in accordance with prevailing deposit rate regulations." 이용 범위는 "retail
  transactions, dining, tourism, education, healthcare, public services, and cross-border
  settlements"로 온·오프라인 전반을 포괄한다고 명시.
- **출처명**: 중국 국무원 영문 뉴스 (english.www.gov.cn)
- **출처 URL**: https://english.www.gov.cn/news/202512/29/content_WS69526d4ec6d00ca5f9a08511.html
- **확인일**: 2026-08-14
- **재조사 1차 (B형 해소 — "예금자보호 대상에 포함")**: 원 출처를 재확인한 결과 다음 문장을
  직접 확인: "These balances will be integrated into banks' regular asset-liability management
  practices and will be protected by deposit insurance, just like ordinary bank deposits." (동일
  URL, 처음 조사 시 발췌 목록에서 누락됐던 문장을 재확인으로 발견). 확인일: 2026-08-14
- **비고**: 발표일이 2025-12-29~30으로 2026 상반기 개시 직전이나, "시행일"이 2026-01-01로
  상반기 첫날이며 본 조사 취지(2026 상반기 중 화제화)에 부합해 채택함.
- **카카오페이 시사점 메모**: CBDC를 "현금 대체"에서 "이자부 예금형 화폐"로 진화시키는 규제
  실험. 국내에서 향후 원화 스테이블코인/CBDC 논의 시, 오프라인 결제 기능과 예금적 성격(이자)을
  동시에 부여하는 모델이 참고사례가 될 수 있음.

## 국내 (구 버전 — 2026-08-14 이전 기준, 카탈로그 채택 제외)

### 1. 네이버페이, '커넥트' 통합 결제단말기로 파리바게뜨 전국 매장 진출

- **유형 태그**: 신규 서비스·기능 / 파트너십·비즈니스모델
- **무엇이 새로운가**: 네이버페이가 전국 3,400여 개 매장을 보유한 파리바게뜨와 오프라인 통합
  단말기 '네이버페이 커넥트' 도입 제휴를 체결했다. 현금·카드·간편결제·NFC뿐 아니라 네이버페이의
  안면인식 결제 '페이스사인'까지 하나의 단말기에서 지원하며, 결제 후 영수증 없이 단말기에서
  바로 네이버 리뷰를 남기고 포인트를 받는 기능도 탑재했다. 대형 프랜차이즈(파리바게뜨)를
  시작으로 소상공인 매장까지 제휴를 확대하겠다고 밝혀, 네이버페이가 자체 통합 단말기로 오프라인
  결제 인프라에 본격 진출한 첫 대형 제휴 사례다.
- **발생 시점**: 2026년 4월 (4월 16일 제휴 발표, 실제 설치는 2026년 하반기 파리바게뜨 직영
  매장부터 순차 예정)
- **원문 발췌**: "'네이버페이 커넥트'는 현금·카드·간편결제·NFC와 안면인식결제 '페이스사인' 등
  다양한 결제 수단을 지원하는 통합 단말기다." / "매장 방문객들은 영수증 없이도 단말기 상에서
  '네이버 리뷰'를 간편하게 남기고 포인트를 받을 수 있다." / "양사는 '네이버페이 커넥트'를 오는
  하반기 중 파리바게뜨 직영매장부터 순차적으로 설치할 예정이다." / "파리바게뜨를 시작으로 대형
  프랜차이즈부터 소상공인 매장까지 전국의 다양한 가맹점에서 '커넥트'를 만날 수 있도록 제휴를
  확대할 것" / [재조사 1차, B형 해소] "전국 3400여개 매장을 보유한 파리바게뜨와 오프라인 통합
  단말기 'Npay 커넥트' 도입을 위한 제휴를 맺었다" (머니투데이 원문 재확인 — 단, 전자신문
  기사에는 이 매장 수 문장이 없고 머니투데이 기사에만 있음. 확인일 2026-08-14)
- **출처명**: 전자신문 / 머니투데이
- **출처 URL**: https://www.etnews.com/20260416000118 ,
  https://www.mt.co.kr/finance/2026/04/16/2026041609200247013
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: 경쟁사가 안면인식결제까지 통합한 자체 결제단말기로 대형
  프랜차이즈에 직접 진입하는 사례. 카카오페이의 오프라인 가맹점 확장 전략(단말기 없는 QR/앱
  중심)과 대비되는 "하드웨어 통합형" 접근으로, 대형 프랜차이즈 대상 단말기 제휴 경쟁이 본격화될
  가능성을 시사.

### 2. 카카오페이, 오프라인 결제 '톱4' 목표 공식 선언 — QR오더·범용 인프라 확대 전략 공개

- **유형 태그**: 브랜드·마케팅·리브랜딩 / 파트너십·비즈니스모델
- **무엇이 새로운가**: 카카오페이가 서울 대한상공회의소에서 열린 미디어 세미나 '페이톡'에서
  오프라인 결제 시장 4위 진입을 공식 목표로 처음 제시했다. 현재 월간 오프라인 결제 이용자
  600만명을 내년까지 1,000만명으로 확대하겠다는 구체적 수치 목표를 밝혔고, QR오더(약 3,000개
  매장 적용, 이삭토스트·파스쿠찌·샐러디 등 신규 프랜차이즈 확정)와 삼성페이·제로페이 연동을 통한
  300만 개 이상 범용 결제 인프라 확보, "굿딜" 데이터 기반 혜택(이용자 372% 증가) 등을 성장
  축으로 제시했다. 카드사와 경쟁이 아닌 "어디서든 쓸 수 있는 환경" 구축을 강조한 점이 기존
  간편결제 vs 카드 구도와 다른 메시지다.
- **발생 시점**: 2026년 5월 (5월 12일)
- **원문 발췌**: "카카오페이는 12일 서울 대한상공회의소에서 열린 미디어 세미나 '페이톡'에서
  오프라인 결제 전략을 공개했다." / "지난해 말부터 본격 도입한 QR오더는 현재 약 3000개 매장에
  적용됐다." / "현재 월간 오프라인 결제 사용자 수는 600만명 수준이며, 카카오페이는 내년까지
  1000만명 확보를 목표로 제시했다." / "카드와 QR결제가 경쟁 관계라기보다는 어디서든 사용할 수
  있는 환경 구축이 중요하다" / [재조사 1차, B형 해소 — "톱4" 프레이밍] 머니투데이: "내년에는
  월 사용자 1000만 명을 달성해 카드사를 포함해 '탑(Top) 4'에 들겠다는 포부도 세웠다." /
  서울신문: "내년까지 오프라인 결제 사용자 1000만명을 달성하고 카드사를 포함한 오프라인 결제
  시장 톱4에 들겠다" (전자신문 기사에는 "톱4" 표현이 없으나 머니투데이·서울신문 두 기사에서
  확인됨. 확인일 2026-08-14) / [재조사 1차, B형 해소 — 신규 프랜차이즈명] 전자신문: "최근
  이삭토스트, 파스쿠찌, 샐러디 등 주요 프랜차이즈에서 적용이 확정됐으며" / 서울신문: "이삭토스트,
  파스쿠찌, 샐러디, 메가MGC커피 등 프랜차이즈로 확산하고 있다" (확인일 2026-08-14) /
  [재조사 1차, B형 해소 — 300만 개 인프라] 전자신문: "삼성페이·제로페이 연동을 통해 300만 개
  이상의 사용처를 확보하며 사실상 대부분의 오프라인 매장에서 이용 가능한 환경을 구축했다" /
  서울신문: "삼성페이·제로페이 제휴를 포함한 300만개 이상 결제처를 확보했다" (확인일 2026-08-14)
  / [재조사 1차, B형 해소 — 굿딜 372%] 전자신문: "굿딜 이용자는 출시 초기 대비 372% 증가했고,
  입점 브랜드도 90개까지 확대됐다" (머니투데이·서울신문에는 이 수치가 없고 전자신문 기사에만
  있음. 확인일 2026-08-14)
- **출처명**: 전자신문 / 머니투데이 / 서울신문
- **출처 URL**: https://www.etnews.com/20260512000285 ,
  https://www.mt.co.kr/finance/2026/05/12/2026051211473328256 ,
  https://www.seoul.co.kr/news/economy/2026/05/12/20260512500271
- **확인일**: 2026-08-14
- **비고**: QR오더 서비스 자체와 밴·포스사와의 'QR오더 얼라이언스'는 2025년 7월 이미 출범한
  기존 서비스로 이번 조사기간(2026 상반기) 이전 시작임. 이번에 채택한 것은 "오프라인 결제 톱4"
  목표 수치와 확대 전략을 공식적으로 처음 밝힌 2026년 5월 12일 이벤트 자체이며, QR오더 얼라이언스
  출범을 새 트렌드로 채택한 것이 아님에 유의.
- **카카오페이 시사점 메모**: (자사 사례) 오프라인 결제 톱4 목표를 대외적으로 공식화한 첫 사례로,
  전사 사업계획 수립 시 이번에 공개된 수치 목표(월간 1000만명, 300만 가맹점 인프라)를 내부
  KPI·투자 우선순위 논의의 참조점으로 활용 가능.

### 3. 카카오페이, 오프라인 신규 가맹점 결제수수료 연내 전액 면제 프로모션

- **유형 태그**: 파트너십·비즈니스모델
- **무엇이 새로운가**: 카카오페이가 연 매출 5억원 이하 영세·중소 신규 오프라인 가맹점을 대상으로
  카카오페이머니 바코드·QR 결제 수수료를 2026년 12월 31일까지 전액 면제하는 프로모션을
  발표했다. 대상은 5월 18일부터 6월 30일까지 신규 가맹 신청·심사를 완료한 매장이며, 최초
  결제 발생 가맹점에는 최대 30% 할인 쿠폰 마케팅 등을 담은 '사장님 성공키트'도 함께 제공한다.
  카카오페이머니 결제액이 전체 거래액의 약 61%를 차지한다는 점에서 실질적 비용 절감 효과를
  노린 소상공인 가맹점 유치 경쟁 신호탄이다.
- **발생 시점**: 2026년 5월 (5월 22일 발표)
- **원문 발췌**: "새롭게 카카오페이 오프라인 결제 가맹점으로 등록한 영세·중소 소상공인 매장"
  / "연 매출규모 5억원 이하의 영세·중소 가맹점" / "올해 12월 31일까지 카카오페이머니 결제
  수수료를 전액 면제" / "지난 18일부터 내달 30일까지 신규 가맹 신청, 심사를 완료한" /
  "카카오페이머니 바코드·QR 결제 수수료" / [재조사 1차, B형 해소 — 30% 쿠폰/성공키트] ZDNet
  Korea: "회차별로 시작일부터 60일 간 카카오페이가 비용을 전액 부담하는 최대 30% 할인 쿠폰
  마케팅" / "마케팅 패키지 '사장님 성공키트'를 증정한다" — 디지털타임스에도 동일 문구 확인:
  "회차별로 시작일부터 60일 간 카카오페이가 비용을 전액 부담하는 최대 30% 할인 쿠폰 마케팅"
  / "가맹 체결 후 첫 카카오페이 결제가 일어난 가맹점에게는 마케팅 패키지 '사장님 성공키트'를
  추가 증정한다" (확인일 2026-08-14) / [재조사 1차, B형 해소 — 61% 결제액] ZDNet Korea:
  "카카오페이머니 결제액은 카카오페이 전체 결제 거래액의 약 61% 수준" (디지털타임스 기사에는
  이 통계가 없고 ZDNet Korea 기사에만 있음. 확인일 2026-08-14)
- **출처명**: ZDNet Korea / 디지털타임스
- **출처 URL**: https://zdnet.co.kr/view/?no=20260522110847 ,
  https://www.dt.co.kr/article/12064042
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: (자사 사례) 신규 가맹점 유치를 위한 수수료 면제는 네이버페이·
  토스 등 경쟁사의 단말기 기반 공세(위 1, 5번 항목)에 대응하는 가맹점 락인(lock-in) 전략으로
  해석 가능. 경쟁사 단말기 제휴 확대 속도와 함께 모니터링할 필요.

### 4. KB금융그룹, 원화 스테이블코인 기반 오프라인 결제·정산·해외송금 통합 기술검증 완료

- **유형 태그**: 규제·정책발 신규 시도 / 신규 서비스·기능
- **무엇이 새로운가**: KB금융그룹이 원화 스테이블코인 발행부터 오프라인 결제, 가맹점 정산,
  해외송금까지 전 과정을 아우르는 통합 기술검증(PoC)을 완료했다. 실생활 결제 모델은 커피전문점
  '할리스' 매장의 오프라인 키오스크 결제로 구현됐으며, 소비자는 별도 디지털 지갑 설치 없이 QR
  코드로 결제하고 정산 단계에서 블록체인 스마트컨트랙트가 자동 실행되는 구조다. 해외송금은
  기존 스위프트(SWIFT) 방식(수시간~수일) 대비 3분 이내로 완료되고 수수료도 약 87% 절감됐다.
  전자결제업체 KG이니시스, 블록체인 플랫폼 카이아, 디지털자산 솔루션 기업 오픈에셋이 참여했다.
- **발생 시점**: 2026년 5월 (5월 17일 발표)
- **원문 발췌**: "기술 검증 과정에는 KG이니시스, 글로벌 레이어1 블록체인 플랫폼 카이아, 디지털자산
  솔루션 기업 오픈에셋 등이 참여했다." / "실생활 결제 모델의 경우 커피전문점 '할리스'의 오프라인
  키오스크 결제를 통해 구현됐다. 소비자는 디지털 지갑이 없이도 QR을 통해 결제할 수 있고, 정산
  단계에서 블록체인 스마트 컨트랙트가 자동 실행된다." / [재조사 1차, B형 해소 — SWIFT 3분/87%
  절감] 뉴시스: "기존 스위프트(SWIFT) 방식에서 수일이 걸렸지만, 이번 검증을 통해 전 과정은
  3분 이내 완료되며" / "수수료는 기존 대비 약 87% 절감됐다" (확인일 2026-08-14)
- **출처명**: 뉴시스
- **출처 URL**: https://www.newsis.com/view/NISX20260517_0003632694
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: 은행지주가 원화 스테이블코인을 오프라인 매장 QR결제에 직접
  실증(할리스 키오스크)한 국내 첫 사례군. 원화 스테이블코인 관련 규제·시범사업이 본격화될 경우
  가맹점 QR 결제 인프라(지갑 미설치 사용자 대응 포함) 요구사항을 가늠할 선행 사례로 참고 가능.

### 5. 토스플레이스, 소형화·매출관리 강화한 2세대 결제단말기 '토스 터미널2' 출시

- **유형 태그**: 신규 서비스·기능
- **무엇이 새로운가**: 토스플레이스가 영수증 출력 겸용 2세대 결제단말기 '토스 터미널2'를
  출시했다. 기존 대비 부피를 약 40% 줄인 콤팩트 설계이면서도 매장 선호도가 높은 3인치 영수증
  출력을 그대로 지원하고, 카드결제를 포함한 모든 간편결제와 매출 리포트 확인을 하나의 기기에서
  처리할 수 있게 했다. 판매는 3월 16일부터 시작됐고, 공식 출시 발표는 4월 6일 이뤄졌다.
- **발생 시점**: 2026년 3~4월 (3월 16일 판매 개시, 4월 6일 공식 출시 보도)
- **원문 발췌**: "기존 대비 부피를 약 40% 줄였다" / "매장 선호도가 높은 3인치 영수증 출력을
  지원한다" / "카드 결제를 포함해 모든 간편결제까지 가능하다" / "결제와 매출 확인을 하나의
  기기에서 처리할 수 있다" / "매출 흐름을 한눈에 파악할 수 있는 리포트 기능도 제공"
- **재조사 1차 (D형 — "3월 16일 판매 개시" 날짜 근거)**: 원 출처 3건(전자신문·머니투데이·
  토스 공식 판매 페이지)을 재확인했으나 etnews·mt.co.kr 두 기사는 "4월 6일 공식 출시" 보도일만
  있을 뿐 "3월 16일 판매 개시"를 직접 언급하지 않음. 토스 공식 판매 안내 페이지
  (toss.oopy.io/325714bb-fde7-8055-a313-eee73013a9ec)는 WebFetch로 재접속 시도 시 반복적으로
  404 오류가 발생해 본문 내용을 직접 인용할 수 없었음. 다만 검색엔진(WebSearch)에 색인된 이
  페이지의 **제목 자체가 "토스 터미널2 판매 개시 안내 (3/16)"**로 표시되어, 토스가 공식적으로
  이 페이지를 3월 16일 판매 개시 공지로 게시했다는 정황 근거는 있음. SBS Biz·FETV 등 대체
  기사 2건도 추가로 확인했으나 "출시"만 언급할 뿐 구체 날짜(3/16)를 명시하지 않음. → **부분
  확인**: 페이지 제목(색인 스니펫)으로는 3월 16일 판매 개시가 뒷받침되나, 본문 원문 발췌를
  직접 인용하지 못해 완전한 B/D형 해소로 보기 어려움. 시도한 방법: ① toss.oopy.io 원문 재접속
  2회(모두 404), ② SBS Biz·FETV·ishopcare.co.kr 대체 기사 3건 확인(날짜 언급 없음), ③ WebSearch
  재검색으로 페이지 제목 확인. 확인일: 2026-08-14
- **출처명**: 전자신문 / 머니투데이 / 토스 공식 판매 안내 페이지
- **출처 URL**: https://www.etnews.com/20260406000189 ,
  https://www.mt.co.kr/finance/2026/04/06/2026040609465456796 ,
  https://toss.oopy.io/325714bb-fde7-8055-a313-eee73013a9ec
- **확인일**: 2026-08-14
- **카카오페이 시사점 메모**: 토스·네이버페이가 나란히 자체 하드웨어(단말기) 소형화·기능 통합
  경쟁에 들어간 시점. 카카오페이가 하드웨어 없는 QR·앱 중심 전략을 유지할지, 자체 단말기
  라인업으로 대응할지에 대한 판단이 필요한 시그널.

### 6. 위챗페이, 한국 제로페이 등 5개국 QR결제망과 상호연동 확대 — 방한 중국 관광객 결제 편의 개선

- **유형 태그**: 파트너십·비즈니스모델 / 규제·정책발 신규 시도
- **무엇이 새로운가**: 중국 텐센트의 위챗페이가 한국 제로페이, 태국 프롬프트페이, 말레이시아
  두잇나우QR, 싱가포르 SGQR+, 스리랑카 랑카QR 등 5개국 QR결제망과 공식 상호연동을 발표했다.
  이에 따라 한국을 방문한 중국인 관광객은 별도의 위챗페이 전용 QR을 찾을 필요 없이 제로페이
  가맹점(스티커)에서 바로 위챗페이로 결제할 수 있게 됐다. 위챗페이 측은 이번 연동이 개별
  가맹점 단위 협력이 아니라 각국 결제 인프라·규제에 부합하는 "전면적 상호연동"이라고 밝혔다.
  2025년 9월 말부터 2026년 6월 말까지 한시 시행된 중국인 무비자 입국 정책과 맞물려 방한
  중국인 관광객의 오프라인 결제 편의성이 실질적으로 확대된 사례다.
- **발생 시점**: 2026년 4월 (4월 23일, 중국 신화통신 발표 기준)
- **원문 발췌**: "한국 등 5개국에서 위챗페이 사용자는 위챗 전용 QR코드를 따로 찾을 필요가
  없어졌다" / "이번 5개국 QR코드 연동은 단순히 개별 가맹점과의 협력이 아니라 각국 결제
  인프라와 규제에 부합하는 전면적인 상호연동을 이룬 것" / [재조사 1차, B형 해소 — 개별
  국가망 명칭] "이번에 발표된 5개국 결제 QR코드는 △한국 제로페이 △태국 프롬프트페이
  △말레이시아 두잇나우QR △싱가포르 SGQR+ △스리랑카 랑카QR이다." (동일 mt.co.kr 기사,
  재확인일 2026-08-14)
- **출처명**: 머니투데이 (중국 신화통신 발표 인용)
- **출처 URL**: https://www.mt.co.kr/world/2026/04/23/2026042312312466974
- **확인일**: 2026-08-14
- **재조사 1차 (무비자 정책, B형)**: 원 출처(mt.co.kr 기사)를 재확인했으나 무비자 입국 정책에
  대한 언급이 전혀 없음을 확인. 대체 출처로 대한민국 정책브리핑(korea.kr)을 새로 찾아 확인함 —
  "다음 달 29일부터 내년 6월 말까지 중국인 단체 관광객에 대해 한시적 무비자 입국이 허용된다."
  / "오는 9월 29일부터 내년 6월 30일까지 중국 단체관광객 대상 무비자 입국을 허용하기로 결정"
  (해당 기사 게재 시점 기준 "다음 달"="9월", "내년"="2026년" — 즉 2025년 9월 29일~2026년
  6월 30일 시행). 카탈로그의 "2025년 9월 말"은 정확히는 "9월 29일"이나 근사치로는 부합.
  출처명: 대한민국 정책브리핑(문화체육관광부 국민소통실) / 출처 URL:
  https://www.korea.kr/news/policyNewsView.do?newsId=148947176 / 확인일: 2026-08-14
- **카카오페이 시사점 메모**: 제로페이 인프라를 매개로 한 외국 QR결제사와의 상호연동이
  국가 단위로 확장되는 추세. 카카오페이가 참여 중이거나 검토할 수 있는 인바운드 외국인 결제
  제휴(알리페이+ 등)의 벤치마크 사례이자, 제로페이 가맹점망이 국경간 결제 연동의 실질적
  게이트웨이 역할을 하고 있다는 점에 주목할 필요.

## 해외 (신규 기준 — 2026-08-14 개정 기준, 검증용 소규모 샘플)

> 이 섹션은 scope.md 개정 판단 기준(참신성/실험성 최우선, 기업 규모 무관, 화제성=반응의
> 온도, 성공사례 불필요)에 따라 새로 조사한 소규모 샘플이다. 목표 개수(5~8건)를 채우지
> 않고 기준에 정확히 부합하는 소수만 채택했다. 국내 3~4건, 해외 3~4건을 시도했으나, 아래
> 상세히 기술하듯 실제로 기준에 부합한다고 판단한 것은 해외 2건뿐이며 국내는 0건이다.
>
> **⚠ 2026-08-14 확대조사 추가**: 위 검증용 소규모 샘플(2건) 이후, 목표치(5~8건)에
> 가깝게 채우기 위해 해외 항목만 추가로 확대 조사했다. NFC 임플란트, 크라우드펀딩
> 스마트링, 초음파 결제, 바이오메트릭 등 다수 각도로 검색했으나 새 기준(특히 "이미 익숙한
> 기술의 지역 확장"을 배제)에 부합하지 않는 후보가 많았고, 최종적으로 3건을 추가 채택
> (3~5번 항목). 확대조사 결과 해외 항목은 총 5건(기존 2건 + 신규 3건)이 됐으며, 언론
> 출처 2건(Cash App Wand, Valerie AI 자판기 — 다만 Valerie는 원 소스가 개발자 X 계정이나
> 직접 접근이 안 돼 크립토 전문매체 보도를 채택), 비언론 출처 1건(아프리카 크립토 자판기 —
> 스타트업 전문 뉴스레터)으로 구성됨.

### 1. Tether × Fasset — 토큰화된 금(XAU₮)과 일상 카드결제를 엮은 "라운드업 골드 적립" Visa 카드

- **유형 태그**: 파트너십·비즈니스모델 (신규 서비스·기능 겸함)
- **왜 참신한가**: "오프라인 카드결제"와 "조각투자(토큰화된 실물자산 — 금)"를 엮어, 결제할
  때마다 잔돈(round-up)이 자동으로 토큰화된 금(XAU₮)에 투자되는 구조를 만들었다. 카드로
  커피 한 잔을 사면 그 거스름돈이 자동으로 금에 적립되는 식으로, "지출 = 소액 실물자산
  투자"라는 새로운 소비자 경험을 오프라인 결제 접점에 이식했다. 스테이블코인 발행사
  (Tether)와 신흥시장 대상 스테이블코인 네오뱅크(Fasset)라는, 전통적 카드 네트워크
  바깥에 있던 두 플레이어가 손잡고 Visa 네트워크에 올라탄 점도 이례적이다. (사용자가
  예시로 든 "스테이블코인과 조각투자 상품을 엮은 결제 비즈니스"와 정확히 부합하는 유형.)
- **무엇이 새로운가**: Tether(테더)와 Fasset(로스앤젤레스 기반 스테이블코인 파워드
  네오뱅크)이 협업해 "세계 최초 금 담보 Visa 네오뱅킹 카드"를 출시했다. 카드 자체는 Visa
  가맹점 어디서나 법정통화로 결제되지만, 거래마다 최대 6%를 XAU₮(테더골드)로 캐시백
  지급하고, 모든 거래의 잔돈을 자동으로 반올림해 XAU₮를 매입하는 라운드업 기능을 탑재해
  일상 소비를 통한 "수동적 금 축적"을 구현했다.
- **발생 시점**: 2026년 6월 (6월 3일 발표)
- **원문 발췌**: "the card will operate on the Visa network, enabling users to spend fiat at
  merchant stores worldwide where Visa cards are accepted" / "earning up to 6% cashback in
  XAU₮ on eligible transactions" / "Users can seamlessly spend their assets in seconds by
  converting XAU₮ to USD₮ and then to fiat" / "the card will feature an automatic round-up
  function that uses the spare change from every transaction to purchase XAU₮, enabling
  continuous, passive gold accumulation through everyday spending"
- **출처명**: Tether.io 공식 보도자료
- **출처 URL**: https://tether.io/news/tether-collaborates-with-fasset-to-launch-the-first-gold-backed-card-unlocking-real-world-utility-for-digital-gold/
- **확인일**: 2026-08-14
- **재조사 1차 (B형 해소 — Fasset "로스앤젤레스 기반" vs "신흥시장 대상")**: 원 출처(tether.io)를
  재접속해 재확인한 결과 "Los Angeles-based"라는 표현은 없으나, "especially in emerging markets
  where currency volatility is a challenge" 및 CEO 인용 "to make Tether Gold the most widely held
  digital gold token in emerging markets"가 확인되어 "신흥시장 대상"이라는 서술은 tether.io
  자체에서도 뒷받침됨. 추가로 대체 출처(CoinDesk, 2026-05-14, 아래 화제성 근거의 URL과 동일)를
  재확인한 결과 "The Los Angeles-headquartered company"라는 문장과 부제 "to expand across
  emerging markets", 본문 "The startup operates a banking and payments platform spanning more
  than 50 corridors across Asia, Africa and the Middle East"를 모두 직접 확인함 — 즉 Fasset은
  "로스앤젤레스에 본사(HQ)를 둔" 회사이면서 동시에 "신흥시장(아시아·아프리카·중동)을 대상으로
  사업을 운영"하는 회사로, 두 서술은 서로 모순되지 않고 각각 본사 소재지·주력 시장이라는 다른
  측면을 가리킴. 카탈로그의 "신흥시장 대상 스테이블코인 네오뱅크" 서술은 이제 원문(CoinDesk,
  tether.io)으로 직접 뒷받침됨. 출처: CoinDesk(재확인, URL은 화제성 근거 절과 동일) / tether.io
  (재확인, 동일 URL). 확인일: 2026-08-14
- **재조사 1차 (D형 해소 — 발생 시점 "2026년 6월 3일 발표")**: 원 출처(tether.io) 페이지를
  재접속해 재확인한 결과 다음 3곳에서 날짜가 직접 확인됨: 기사 상단 메타데이터 "June 3, 2026",
  본문 dateline "3 June 2026", 카테고리 메타정보 "2026-06-03"(처음 조사 시 발췌 목록에서
  누락됐던 날짜 표기를 재확인으로 발견). 확인일: 2026-08-14
- **화제성 근거**: 보도자료 배포량 자체는 크지 않으나(테더/파셋 공식 채널 및 소수
  암호화폐 전문매체), Fasset이 2026년 5월 14일 시리즈B $51M 투자 유치(SBI Group,
  Investcorp 등 참여) 소식과 맞물려 크립토·핀테크 업계 매체(CoinDesk, BigGo Finance,
  TechAfrica News, Zawya 등) 다수가 "세계 최초"라는 프레이밍으로 별도 보도했다는 점에서
  업계 내 반응은 있었으나, 일반 소비자 커뮤니티 단위의 논쟁·입소문 정황까지는 확인하지
  못했다. → 화제성 근거는 "업계 매체 교차보도" 수준이며, 소비자 단위 화제성은 약함 —
  참신성(스테이블코인 발행사가 조각투자 금과 카드결제 라운드업을 결합)을 주된 채택
  근거로 삼음. 출처: CoinDesk(2026-05-14) https://www.coindesk.com/business/2026/05/14/stablecoin-powered-neobank-fasset-raises-usd51-million-to-expand-across-emerging-markets
  (확인일 2026-08-14)
- **카카오페이 시도 아이디어**: 카카오페이머니/카카오페이포인트 결제 시 잔돈을 자동으로
  적립·투자하는 "라운드업" 기능은 이미 유사 사례가 있으나, 이를 "토큰화된 실물자산"과
  엮은 사례는 국내에 없다. 예컨대 카카오페이가 제휴 조각투자 플랫폼(금·부동산 등)과
  손잡고, 오프라인 QR·바코드 결제 시 잔돈을 자동으로 조각투자 상품에 적립하는 기능을
  파일럿으로 시도해볼 수 있다 — "결제할 때마다 실물자산에 소액 투자된다"는 스토리텔링을
  오프라인 결제 UX에 직접 이식하는 방식.

### 2. 대만 iPass — 플로피디스크 등 "말도 안 되는" 폼팩터 시리즈 교통·결제카드 (참고용, 시점 caveat 있음)

- **유형 태그**: UX/인터페이스 패턴 (신규 서비스·기능 겸함 — 결제카드의 물리적 폼팩터 실험)
- **왜 참신한가**: 결제/교통카드라는 기능적 사물을, "이제는 아무도 안 쓰는 옛날 저장매체
  (플로피디스크)"를 1:1 스케일로 재현한 수집품·굿즈로 재해석했다. 이전에도 모토로라
  다이나택(최초 휴대폰), 기차 모형, 조리개(플립플롭), 울트라맨 베타캡슐, LED 고질라
  스노우글로브, 혈액백 등 "결제 기능과 전혀 무관한 사물·밈"을 카드 폼팩터로 만들어온
  시리즈의 연장선으로, "결제수단 자체를 수집·굿즈 문화의 대상으로 만든다"는 조합이
  참신하다. 대형 카드사·핀테크가 아니라 대만의 지역 교통카드 발행사가 주도한다는 점도
  특징.
- **무엇이 새로운가**: 대만 교통카드 발행사 iPass가 NFC 기반 선불 교통·결제카드를
  3.5인치 플로피디스크와 1:1 크기로 재현한 한정판(검정·노랑 2종)을 출시했다. 대만 전역
  버스·지하철·택시·공유자전거는 물론 7-Eleven·FamilyMart 등 편의점, 마트, 약국,
  맥도날드·버거킹 등 패스트푸드 체인에서 실제 결제 수단으로 쓸 수 있다. 제품 설명에는
  "이 제품은 카드 기능만 있으며 실제 디스크(저장) 기능은 없다"는 안내 문구까지 붙었다.
- **발생 시점**: 2025년 12월 24일(크리스마스 이브) 판매 개시 — **⚠ 조사기간(2026년
  1~6월) 이전 출시임을 명시.** 다만 이에 대한 국제 기술 매체 보도·커뮤니티 논의는
  2025년 12월 27일(Slashdot)부터 2026년 1월 28일(Hackaday, 댓글 26개)까지 이어지며
  2026년 1월에도 "화제화"가 지속됐다는 정황이 있어 참고용으로 기록함. 엄밀한 "2026
  상반기 신규" 기준에는 부합하지 않을 가능성이 높으므로, report-writer/fact-checker가
  채택 여부를 별도 판단할 것을 권고(scope.md의 D형 판단 대상).
- **원문 발췌**: "The floppy disk joins an increasingly absurd lineup of iPass form factors.
  Previous releases have included... a Motorola DynaTAC replica, model trains, a flip-flop,
  an LED-lit Godzilla snow globe, and a blood bag." / "This product only has a card function
  and does not have a 3.5mm [sic] disk function, please note before purchasing." (제품
  경고문) / "went on sale starting Christmas Eve and comes in black or yellow finishes at
  1:1 scale... works across Taiwan's public transport network -- buses, trains, subways,
  taxis, and bike rentals -- as well as convenience stores like 7-Eleven and FamilyMart,
  supermarkets, pharmacies, and fast-food chains including McDonald's and Burger King."
- **출처명**: Tom's Hardware / Slashdot(it.slashdot.org) / Hackaday
- **출처 URL**: https://www.tomshardware.com/pc-components/storage/floppy-disk-pre-paid-cash-card-launched-in-taiwan-nfc-payment-method-only-has-a-card-function-warns-supplier-so-keep-it-out-of-your-fdd ,
  https://it.slashdot.org/story/25/12/27/0236249/taiwans-ipass-releases-floppy-disk-pre-paid-cash-card ,
  https://hackaday.com/2026/01/28/the-fancy-payment-cards-of-taiwan/
- **확인일**: 2026-08-14
- **재조사 1차 (B형 — 이전 시리즈 목록 "울트라맨 베타캡슐" 오류 확인, 정정 필요)**: 원 출처
  3건(Tom's Hardware, Slashdot, Hackaday)을 재접속·WebSearch로 재확인했으나 세 곳 모두
  "Previous releases have included a Motorola DynaTAC replica, model trains, a flip-flop, an
  LED-lit Godzilla snow globe, and a blood bag."로 동일하게 "a flip-flop"만 언급하며 "Ultraman
  Beta Capsule"/"울트라맨"이라는 단어는 세 원출처 어디에도 없음(Hackaday 기사 직접 재접속으로도
  재확인, WebSearch로 재인용된 동일 문구도 "flip-flop"으로 일치). 참고로 "울트라맨 베타캡슐
  iPass 카드" 자체는 Pinkoi·eBay 판매 페이지에서 확인되는 실존 iPass 카드 상품이나(LED 발광
  기능, 한정판, 대만 교통·편의점 결제 지원 — 별도 실물 상품으로는 존재), 이번 "플로피디스크 카드
  이전 시리즈"를 나열한 기사들의 목록에는 포함되어 있지 않음. 즉 evidence 자체의 "왜 참신한가"
  필드에 있던 "울트라맨 베타캡슐"은 원 출처와 무관하게 잘못 기재된 것으로 판정됨. →
  **report-writer는 카탈로그의 "울트라맨 베타캡슐"을 "flip-flop"으로 정정할 것을 권고.** 참고로
  "flip-flop"은 "조리개"(카메라 부품)가 아니라 쪼리/플립플롭 샌들을 의미하므로, evidence 상단
  "왜 참신한가" 필드의 "조리개(플립플롭)"라는 표기도 오역이며 함께 정정이 필요함. 확인일:
  2026-08-14
- **재조사 1차 (B형 해소 — "Hackaday 댓글 26개")**: 원 출처
  (hackaday.com/2026/01/28/the-fancy-payment-cards-of-taiwan/)를 재접속해 재확인한 결과, 페이지
  제목에 "26 Comments"로 명시되어 있어 댓글 26개가 정확히 확인됨(처음 조사 시 발췌 목록에서
  누락됐던 표기를 재확인으로 발견). 확인일: 2026-08-14
- **화제성 근거**: Slashdot 게시물(2025-12-27)과 Hackaday 게시물(2026-01-28, 댓글 26개)이
  약 한 달 간격을 두고 각각 별도로 이 소재를 다뤘고, Hackaday 댓글에서는 일본 Suica,
  태국 PromptPay, 인도 UPI 등 타국 결제시스템과 비교하는 토론이 이어졌다 — 보도자료
  재배포가 아니라 국제 기술 커뮤니티(해커/개발자 성향 독자층)의 자발적 화제화 정황이
  뚜렷하다. 다만 시점이 조사기간 경계(2025년 12월~2026년 1월)에 걸쳐 있어 "2026 상반기
  신규"라는 기준에는 온전히 부합하지 않을 수 있음을 재차 명시.
- **카카오페이 시도 아이디어**: 카카오페이 실물카드/카카오페이머니 카드(있다면)나 제휴
  선불카드를, 결제 기능과 무관한 "밈·추억 소재"(예: 카카오프렌즈 굿즈를 넘어 "삐삐",
  "옛날 다이얼 전화기", "5.25인치 플로피디스크" 등 복고 오브젝트) 형태로 한정판
  제작해보는 실험. 카카오페이의 강점인 카카오프렌즈 IP와 결합하면, "기능은 그대로,
  껍데기는 완전히 딴 세상"이라는 이 조합을 국내 정서에 맞게 변형할 여지가 크다.

### 3. Block(Cash App) — 틱톡 DIY "마법봉 결제" 밈을 그대로 공식 상품화한 탭투페이 액세서리 'Cash App Wand'

- **유형 태그**: UX/인터페이스 패턴 (신규 서비스·기능 겸함) — 커뮤니티발 밈을 그대로 정식
  제품화
- **왜 참신한가**: 결제수단은 원래 "잘 숨겨서 안전하게 보관하는 것"이 상식인데, 이 제품은
  거꾸로 "과시하고 다니는 것"으로 만들었다. 더 특이한 점은 이 아이디어의 출처다 — Cash App이
  먼저 기획한 게 아니라, 2025년 말 틱톡·인스타그램에서 이용자들이 직접 데코 지팡이(완드)
  안에 카드를 몰래 심어 결제하는 영상을 찍어 올리는 DIY 밈이 먼저 유행했고, 회사가 그
  자발적 커뮤니티 밈을 그대로 정식 유료 상품($25)으로 공식화했다. "회사가 트렌드를
  만드는 게 아니라 커뮤니티가 만든 밈을 회사가 뒤늦게 상품화한다"는 순서 자체가 이례적이며,
  실제 반응도 "재밌다"는 호응과 "분실·강도 위험", "금융 유치화(infantilization)"라는
  비판이 동시에 뜨겁게 갈렸다.
- **무엇이 새로운가**: Block의 Cash App이 진주빛(pearlescent) NFC 칩 내장 열쇠고리형
  액세서리 "Cash App Wand"를 출시했다. Cash App 카드에 연동된 NFC 칩을 담아 비자 탭투페이
  가맹점 어디서나 1초 안에 결제할 수 있고, 배터리·블루투스 없이 앱에서 최초 1회 활성화만
  하면 독립적으로 작동한다. 13세 이상 Cash App 카드 보유자 대상, 수량 한정 판매.
- **발생 시점**: 2026년 6월 4일 (목요일 출시)
- **원문 발췌**: "The wand launched on Thursday, June 4, 2026, priced at $25." / "paying for
  items in the real world with a tap of a homemade magic wand, which hides a tap-and-pay credit
  card" (밈의 기원 서술) / "Cash App Tags are just the opposite. We see a unique opportunity
  here to make payments visible and social for the first time." — Thomas Templeton, Hardware
  Lead, Block / (비판 기사에서) "flaunting your payment device on a bag screams DANGER, making
  you ripe for robbing, and I sense that a plastic magic wand will be easier to lose than a
  carefully stowed-away bank card." / "Cash App's Tags appeal to a juvenile sense of
  finance...it's fun. The dopamine of tapping a whimsical little wand is far more appealing than
  a card payment, making impulse buys feel joyful, but inconsequential." / "tapping to pay
  should feel a little more like magic" — Thomas Templeton, X(트위터) 게시물 인용
- **출처명**: TechCrunch / Yahoo Tech(Yahoo Finance 소속 기술 코너) / Creative Bloq
- **출처 유형**: 언론 (TechCrunch, Yahoo Tech, Creative Bloq 모두 전통 매체) — 다만 상품
  기획의 원천이 된 밈 자체는 2025년 말 틱톡·인스타그램(비언론 채널)에서 자발적으로
  발생했다는 점에 주목할 것
- **출처 URL**: https://techcrunch.com/2026/06/04/cash-app-launches-a-wand-for-tap-and-pay/ ,
  https://tech.yahoo.com/apps/articles/cant-trusted-cash-apps-magic-130000956.html ,
  https://www.creativebloq.com/design/branding/cash-app-swaps-boring-bank-cards-for-magic-wands
- **확인일**: 2026-08-14
- **화제성 근거**: TechCrunch·Yahoo Tech·Creative Bloq 등 다수 매체가 출시 당일~수일 내
  각각 별도로 다뤘고, 그중 Yahoo Tech 기사는 단순 소개가 아니라 "나는 이 마법봉을 믿을 수
  없다(I can't be trusted with Cash App's new magic wand)"는 제목의 비판적 오피니언 형태로
  안전 우려·금융 유치화 논쟁을 담았다. 담당 임원(Templeton)이 X에 직접 해명성 게시물을
  올린 점도 논쟁이 실제로 있었음을 시사한다. 다만 이는 원 트렌드(틱톡 DIY 밈)가 2025년 말
  발생했고, 이번 항목은 그것을 "회사가 공식 상품화"한 2026년 6월 사건을 대상으로 함에
  유의.
- **카카오페이 시도 아이디어**: 카카오페이머니 카드를 "숨기지 않고 과시하는" 굿즈형
  액세서리로 재해석 — 카카오프렌즈 IP와 결합한 NFC 탭투페이 열쇠고리·펜던트를 한정판으로
  내놓아 "결제를 패션 아이템화"하는 Z세대 트렌드에 대응하는 실험을 해볼 수 있다. 다만 이
  사례가 동시에 보여주듯 분실·도난 시 즉시 원격 잠금이 가능한 안전장치를 반드시 함께
  설계해야 한다는 반면교사이기도 하다.

### 4. Valerie — 오픈소스 AI 에이전트(OpenClaw)가 상품선정·가격결정·정산까지 전권 행사하는 자율운영 자판기

- **유형 태그**: 신규 서비스·기능 (파트너십·비즈니스모델 겸함 — 무인 오프라인 결제 접점의
  운영주체 자체가 AI로 완전 이전)
- **왜 참신한가**: 자판기 자체는 흔하지만, 이 사례는 사람이 전혀 개입하지 않고 AI
  에이전트가 상품 구성·가격 결정·광고 제작·판매 추적·계좌 관리까지 전 과정을 자율적으로
  수행한다는 점에서 "오프라인 결제 = 사람이 정한 가격에 사람이 돈을 낸다"는 전제 자체를
  깬다. 대기업이 아니라 개인 개발자가 오픈소스 프레임워크로 만든 프로젝트라는 점도
  scope 기준(기업 규모 무관, 오히려 작을수록 좋은 신호)에 부합하며, 무엇보다 "성공
  사례"가 아니라 보안업체가 "크립토 지갑 탈취 위험"을 실제로 경고하며 논란이 된 시도라는
  점이 특징적이다.
- **무엇이 새로운가**: 개발자 Chris van der Henst(X 계정 @cvander)가 오픈소스 AI 에이전트
  프레임워크 OpenClaw를 이용해 만든 AI "Valerie"가 샌프란시스코 Frontier Tower의 실물
  자판기를 사람 개입 없이 자율 운영한다. Valerie는 무엇을 팔지 정하고, 상품명을 짓고,
  가격을 책정하고, 광고를 만들고, 판매를 추적하며, 자체 인스타그램 계정과 은행 계좌까지
  직접 관리한다. 수요가 몰리면 스스로 가격을 올리는 등 실시간 동적 가격결정 행동도
  관찰됐다.
- **발생 시점**: 2026년 4월 (4월 15일 crypto.news 보도 기준. 자판기 운영 개시 자체의
  정확한 일자는 원 출처에서 확인되지 않음 — 보도 시점을 기준으로 채택)
- **원문 발췌**: "decides what to sell, names the products, sets the prices, creates the ads,
  and tracks every sale" / "it even put the prices way up, and justified it because people kept
  buying" / "runs her own Instagram and controls her own bank account" / 보안 경고: "unauthorized
  actions, data exposure, system compromises and drained crypto wallets" — CertiK 등 보안
  연구자 인용, "over 130,000 internet-exposed OpenClaw instances" 및 "more than 280 security
  advisories and 100 CVEs since launch"
- **출처명**: crypto.news
- **출처 유형**: 언론(크립토 전문매체) — 원 소스는 개발자 X 계정(@cvander)의 게시물 및
  Valerie 전용 웹사이트(valerie.reventlov.ai)·개발자 블로그(blog.reventlov.ai)이나, 두
  사이트 모두 접속 시도(DNS 조회 실패, 2회) 결과 직접 접근이 불가해 이를 보도한 크립토
  전문매체 기사를 근거로 채택함. 참고로 동일 사실을 Bitget·Bitmart·note.com(일본어
  매체) 등도 별도로 보도함.
- **출처 URL**: https://crypto.news/ai-vending-agent-valerie-runs-san-francisco-vending-machine-with-openclaw/
- **확인일**: 2026-08-14
- **재조사 1차 (B형 해소 — "GitHub 스타 25만 개 이상, 사용자 30만~40만 명")**: 원 출처
  (crypto.news, 위 URL과 동일)를 재접속해 재확인한 결과 다음 문장을 직접 확인: "OpenClaw itself
  has quickly become one of the most prominent agent frameworks in crypto‑adjacent circles since
  its public release in November 2025, amassing more than 250,000 GitHub stars and an estimated
  300,000 to 400,000 users as it spreads from developers to Web3 firms." (동일 URL, 처음 조사 시
  발췌 목록에서 누락됐던 문장을 재확인으로 발견). 확인일: 2026-08-14
- **재조사 1차 (D형 해소 — "crypto.news 2026년 4월 15일 보도")**: 원 출처(crypto.news) 페이지를
  재접속해 재확인한 결과 저자(Andrew Folkler) 바로 아래 byline에 "Apr 15, 2026 at 5:51 PM UTC"로
  게시 시각까지 명시되어 있어 보도일이 정확히 확인됨. 자판기 실제 운영 개시일 자체는 여전히
  원문 어디에도 별도로 명시되어 있지 않아, 기존 caveat("자판기 운영 개시 자체의 정확한 일자는
  원 출처에서 확인되지 않음 — 보도 시점을 기준으로 채택")은 그대로 유지함. 확인일: 2026-08-14
- **화제성 근거**: 기반 프레임워크인 OpenClaw 자체가 2025년 11월 공개 이후 GitHub 스타
  25만 개 이상, 사용자 30만~40만 명을 확보한 크립토 업계 화제의 오픈소스 프로젝트다.
  Valerie 사례는 X(트위터)에서 먼저 확산된 뒤 crypto.news·Bitget·Bitmart·note.com 등
  여러 매체가 각각 독립적으로 다뤘고, 보안업체 CertiK이 "OpenClaw류 에이전트가 크립토
  지갑을 탈취할 수 있다"는 경고를 발표하며 실제 논쟁으로 이어졌다(13만 개 이상 노출된
  OpenClaw 인스턴스, CVE 100건 이상 확인). 단순 홍보성 보도가 아니라 보안 논란까지
  포함된 실질적 화제화 정황이 뚜렷하다.
- **카카오페이 시도 아이디어**: 무인 자판기·사내 카페테리아 키오스크 등 제한된 범위에서
  AI 에이전트가 재고·가격·프로모션을 자율 결정하는 소규모 파일럿을 시도해볼 수 있다.
  다만 Valerie 사례가 동시에 보여주듯, AI가 금융 계좌·결제 수단을 직접 통제할 때 발생할
  수 있는 보안 취약점(계정 탈취, 무단 결제 등)에 대한 가드레일을 먼저 설계해야 한다는
  반면교사이기도 하다.

### 5. Innovative Vending Solutions × MoneyBadger — 아프리카 대륙 최초, 비트코인 라이트닝 결제 자판기

- **유형 태그**: 신규 서비스·기능 (파트너십·비즈니스모델 겸함)
- **왜 참신한가**: 대형 카드사나 글로벌 벤딩 벤더가 아니라, 케이프타운의 소규모 자판기
  업체(2015년 껌볼 자판기 한 대로 창업)와 스텔렌보스의 소규모 비트코인 스타트업(2022년
  설립)이 손잡고 만든 "아프리카 대륙 최초" 크립토 지원 자판기다. 자판기·크립토 결제
  각각은 새롭지 않지만, 이 조합을 상용 무인판매기에 실제로 이식해 아프리카에서 처음
  선보였다는 점, 그리고 대기업이 아닌 로컬 스타트업 간 협업이라는 점이 scope의 "기업
  규모 무관, 작을수록 좋은 신호일 수 있다" 기준에 정확히 부합한다.
- **무엇이 새로운가**: 터치스크린에서 상품을 고르고 비트코인 라이트닝 네트워크 또는
  크립토 지갑 QR코드를 스캔하면 즉시 상품이 배출되는 자판기. Innovative Vending
  Solutions의 TM4 터치스크린 모델에 자체 개발 앱을 얹었고, MoneyBadger가 크립토 결제
  레일(정산)을 담당한다.
- **발생 시점**: 2026년 6월 (뉴스레터 게재일 2026-06-12 기준 "이제 막 출시(just
  launched)"로 서술 — 정확한 출시 일자는 원문에 명시되지 않음)
- **원문 발췌**: "Customers tap the touchscreen, select a product, scan a QR code from a
  Bitcoin Lightning or crypto wallet, and the machine dispenses the item instantly." / "SA's
  crypto infrastructure is quietly maturing into real consumer use cases." / (신뢰도 참고)
  "Innovative Vending's previous Revlon promotional machine went viral on LinkedIn." / 시장
  맥락: MoneyBadger는 1,600개 이상 소매 거점에서 결제 레일로 쓰이며, Pick n Pay에서만
  "over R1m a month in Bitcoin payments"(월 100만 랜드 이상 비트코인 결제)가 발생. 남아공
  크립토 보유율은 약 12.4%로 서술됨.
- **출처명**: The Open Letter (theopenletter.io)
- **출처 유형**: 비언론 (스타트업/핀테크 전문 뉴스레터·블로그 — Substack 유사 개인/소규모
  발행 매체로 추정)
- **출처 URL**: https://theopenletter.io/p/crypto-enabled-vending-machine
- **확인일**: 2026-08-14
- **재조사 1차 (D형 해소 — "뉴스레터 게재일 2026-06-12")**: 원 출처(theopenletter.io) 페이지
  자체에는 게시일이 표시된 byline이 없어(저자명 "Jason Mill"만 표시) WebFetch 재접속만으로는
  날짜를 직접 확인할 수 없었으나, 사이트의 sitemap.xml(https://theopenletter.io/sitemap.xml)을
  재접속해 해당 URL 항목의 lastmod 값을 직접 확인함 — "<loc>https://theopenletter.io/p/
  crypto-enabled-vending-machine</loc><lastmod>2026-06-12</lastmod>". 독립적으로 두 차례의
  WebSearch 재검색에서도 "게시일 2026년 6월 12일"이 검색엔진 인덱스 메타데이터 기반으로
  일관되게 나타나 sitemap 값과 부합함(교차 확인). 다만 sitemap의 "lastmod"는 엄밀히는 "최종
  수정일"이며 최초 "게시일"과 이론상 다를 수 있다는 점은 유의 — 신규 발행 뉴스레터 특성상 별도
  수정 이력이 없다면 최초 게시일과 동일할 가능성이 높다고 판단함. 확인일: 2026-08-14
- **비고(화제성 근거의 한계)**: 이 자판기 자체에 대한 소비자 단위 SNS 반응(댓글 수·조회수
  등) 지표는 확인하지 못했다 — 뉴스레터는 같은 업체의 "이전" 프로모션 자판기(Revlon 무료
  샘플 자판기)가 LinkedIn에서 바이럴됐다는 사실을 이 업체의 화제성 있는 이력으로 인용할
  뿐, 이번 크립토 자판기 자체의 확산 정황을 직접 제시하지는 않는다. 따라서 이 항목은
  "화제성"보다 "참신성"(소규모 로컬 스타트업 협업 + 아프리카 대륙 최초 + 이미 실사용
  기반이 갖춰진 크립토 결제 인프라와의 결합)을 주된 채택 근거로 삼았음을 명시한다.
- **카카오페이 시도 아이디어**: 국내 무인 자판기·편의점 자판기에 원화 스테이블코인/
  디지털자산 QR결제를 파일럿으로 붙여보는 실험. 대형 벤딩머신 사업자가 아니어도, 지역
  소규모 벤딩 스타트업과의 소규모 제휴로 리스크를 낮춰 시도해볼 수 있는 모델이며, 남아공
  사례처럼 "이미 존재하는 소액결제 인프라(카카오페이머니)를 새로운 무인 접점에 이식"하는
  방식으로 응용 가능.

## 국내 (신규 기준 — 2026-08-14 개정 기준, 검증용 소규모 샘플)

> **국내는 0건 채택.** 아래 "미채택 사유"에 시도한 검색 전략과 각 후보가 왜 새 기준에
> 부합하지 않는다고 판단했는지를 기록한다. 억지로 채우지 않고 있는 그대로 보고한다.
>
> **⚠ 2026-08-14 비언론 채널 확대조사로 아래 2건 신규 채택** (하단 "국내 (신규 기준 —
> 비언론 채널 확대조사)" 절 참고). 위 "0건" 결론은 이번 확대조사 이전 소규모 샘플
> 기준이었으며, 확대조사 결과와 함께 감사 추적을 위해 원문은 수정하지 않고 그대로 둔다.

## 국내 (신규 기준 — 비언론 채널 확대조사, 2026-08-14)

> 직전 소규모 샘플(위 절)이 언론 기사 중심 검색으로 국내 0건에 그친 데 대한 후속
> 조치로, scope.md의 "출처 채널 — 비언론 채널 적극 활용" 지침에 따라 브런치·velog,
> 와디즈, 디스콰이엇·프로덕트헌트, 유튜브, GeekNews·OKKY, 더쿠·인스티즈·에펨코리아·
> 클리앙, 트위터(X)/스레드, 대학생 창업 공모전·해커톤, 엔젤/시드 투자·액셀러레이터
> 선정 공시 등 40회 이상의 개별 검색을 추가로 시도했다. 결과적으로 순수 비언론
> 채널(개인 블로그·커뮤니티·SNS 게시물 원문)에서 기준에 부합하는 사례는 발견하지
> 못했으나, **스타트업 전문 매체(벤처스퀘어) 보도 + 정부 액셀러레이터(TIPS) 선정
> 공시를 교차 확인한 소규모 스타트업 사례 1건**, **대학 예비창업패키지 선정기업을
> 다룬 매거진 기사 1건**을 참신성 기준에 부합한다고 판단해 채택한다. 두 건 모두
> "언론"으로 분류하되 전통 경제지가 아닌 스타트업 특화 매체/커리어 매거진이라는 점을
> 출처 유형에 명시하며, 순수 비언론(개인 채널)에서는 끝내 채택 가능한 사례를 찾지
> 못했다는 한계를 솔직히 기록한다.

### 1. 루트파인더즈 — 화면·비밀번호 없이 목소리만으로 본인인증+결제를 완결하는 'TTP(Talk To Pay)'

- **유형 태그**: 신규 서비스·기능 (규제·정책발 신규 시도 겸함 — 정부 R&D/액셀러레이터
  선정 기반 개발)
- **왜 참신한가**: 국내 간편결제 업계의 생체인증 결제 경쟁(삼성페이 지문, 네이버
  페이스사인·토스 페이스페이의 얼굴인식)이 전부 "화면+카메라/센서"를 전제로 하는
  것과 달리, 이 기술은 화면 확인이나 비밀번호·보안키패드 입력 자체를 없애고 오직
  "목소리"만으로 본인인증부터 결제 완료까지 끝낸다. 시각장애인 등 화면·문자 기반
  인터페이스 이용이 어려운 사용자를 최초 타겟으로 설계했다는 점도 기존 생체인증
  결제(속도·편의 중심)와 다른 "접근성 중심" 문제 정의다. 대기업이 아니라 시각장애인
  콘텐츠 접근성 플랫폼을 만들어온 소규모 스타트업이 본업의 연장선에서 개발 중이라는
  점도 특징.
- **무엇이 새로운가**: 루트파인더즈(시각장애인용 콘텐츠 플랫폼 '이지플러스' 개발사)가
  음성만으로 사용자 인증과 결제를 동시에 처리하는 AI 기반 기술 'TTP(Talk To Pay)'
  개발에 착수했다. 음성 워터마킹, AES 기반 암호화, 실시간 위조(합성) 음성 검출
  기술을 결합해 보이스피싱·AI 합성음성 사기 위험에 대응하는 자체 보안 구조를 갖췄다.
  중소벤처기업부 '팁스(TIPS) R&D 일반트랙'과 카카오뱅크 '2026 핀넥트 이노베이션
  스쿨' 참여기업으로 선정돼 개발 자금·인프라를 지원받는다.
- **발생 시점**: 2026년 5월 (5월 19일 보도 — TIPS R&D 선정 및 TTP 개발 착수 발표)
- **원문 발췌**: "사용자의 목소리를 기반으로 본인 여부를 확인하고 결제까지 진행하는
  차세대 인증 기술" / "비밀번호 입력이나 보안 키패드, 다단계 인증 절차 없이 음성만으로
  인증부터 결제 완료까지" / "TTP는 복잡한 인증 절차를 줄이면서도 사용자의 편의성과
  보안성을 동시에 강화하기 위한 기술" — 김종국 루트파인더즈 대표 / "음성 워터마킹
  기술과 AES 기반 암호화 시스템을 함께 적용해 보안성을 강화했다" (벤처스퀘어,
  2026-05-19). 동일 사실을 다룬 소셜밸류(socialvalue.kr, 기사승인 2026-05-19
  14:59:28) 기사에도 "실시간 위조 음성 검출 기술로 보이스피싱과 AI 합성 음성 범죄를
  방지" / "중소벤처기업부 '팁스(TIPS) R&D 일반트랙'과 카카오뱅크의 '2026 핀넥트
  이노베이션 스쿨' 참여 기업으로 선정되어 개발 중" 문구로 교차 확인됨.
- **출처명**: 벤처스퀘어(VentureSquare) / 소셜밸류(SocialValue)
- **출처 유형**: 언론(스타트업 전문 매체 — 전통 경제지가 아닌 스타트업 생태계 특화
  매체 2곳의 교차보도. 순수 비언론(개인 블로그·커뮤니티) 채널에서는 이 사례를 다룬
  게시물을 발견하지 못함)
- **출처 URL**: https://www.venturesquare.net/1083257 ,
  https://www.socialvalue.kr/news/view/1065592776459973
- **확인일**: 2026-08-14
- **화제성 근거**: 전통 경제지 보도는 확인되지 않았고, 스타트업 전문 매체 2곳의
  독립 보도로 교차 확인됨. 일반 소비자 커뮤니티·SNS 단위의 화제화 정황은 검색으로
  찾지 못했다(회사 자체가 아직 R&D 착수 단계라 대중 노출이 제한적인 것으로 추정).
  **화제성 근거는 약하다는 점을 솔직히 밝히며, 채택 근거는 전적으로 참신성(화면·
  비밀번호 없는 순수 음성 인증+결제 조합은 국내 간편결제 업계에서 확인된 사례가
  없음)에 둔다.**
- **카카오페이 시도 아이디어**: 카카오페이는 이미 카카오뱅크 액셀러레이터
  프로그램('핀넥트 이노베이션 스쿨')을 통해 이 스타트업과 접점이 있을 가능성이 높다.
  카카오페이 오프라인 결제에도 "화면을 보지 않고" 결제하는 시나리오(예: 시각장애인
  가맹점주·고령층 이용자, 운전 중 하이패스 없는 톨게이트 등)를 상정한 음성 인증+결제
  파일럿을 소규모로 실험해볼 수 있다 — 특히 접근성 이슈는 ESG·상생금융 메시지와도
  결합하기 쉬운 소재.

### 2. 리틀핀 — 여러 카드를 한 거래에서 나눠 긁는 '결합(분할)결제' 앱 '페이랩(Paywrap)' (참고용, 화제성·출시 전 caveat 큼)

- **유형 태그**: 신규 서비스·기능
- **왜 참신한가**: 기존 간편결제는 "결제수단 1개 선택 → 결제"가 기본 구조인데,
  페이랩은 소비자가 보유한 여러 카드(예: 삼성카드+현대카드)를 원하는 비율로 나눠
  **한 번의 결제 트랜잭션 안에서 동시에** 사용할 수 있게 한다는 점이 특징이다.
  단순 포인트 분할이 아니라 "카드사별 실적 조건을 동시에 채우기 위한 결제 포트폴리오
  구성"이라는, 카드 리워드 최적화를 결제 UX 자체에 내장한 접근이 참신하다.
  대기업이 아니라 2025년 설립된 소규모 스타트업(경남 진주바이오진흥원 소재)이 예비
  창업패키지 지원을 받아 개발 중이라는 점도 특징.
- **무엇이 새로운가**: 리틀핀(대표 김영석)이 "결제자가 보유한 결제 수단을 원하는
  만큼 동원해 한 번에 결제할 수 있는" 모바일 간편결제 서비스 '페이랩'을 개발
  중이다. 예: 200만원 결제 시 삼성카드 100만원+현대카드 100만원으로 나눠 한 번에
  결제해 양쪽 카드 실적 조건을 동시에 충족시키는 방식.
- **발생 시점**: 2026년 3월 (3월 15일 매거진한경 보도 — 인천대 예비창업패키지
  선정기업 소개 기사에서 최초 공개 확인) — **⚠ 정식 출시는 2027년으로 예정돼 있고
  기사 시점 기준 "초기 모델 개발 완료" 단계에 불과함. 결제 API 연동 파트너사(대기업
  3곳)와 논의 중이나 실제 상용 서비스·데모는 아직 없는 컨셉/개발 단계 항목임.**
- **원문 발췌**: "결제자가 보유한 결제 수단을 원하는 만큼 동원해 한 번에 결제할 수
  있는 모바일 간편결제 서비스" (리틀핀이 자체 명명한 '결합(분할)결제') / "페이랩은
  '편리함에 차별화된 결제 기능'을 더했다는 점이 경쟁력입니다." / "결제에 따른 리워드
  설계를 소비자가 직접 할 수 있다"(예시로 삼성카드·현대카드 동시 실적 달성 언급) /
  회사 설립: 2025년 5월. 정식 출시 계획: 2027년, 글로벌 진출 목표: 2028년. 기사
  시점 기준 "결제 API 진입을 도와줄 파트너사"를 찾는 단계이며 대기업 3곳과 협업
  논의 중.
- **출처명**: 매거진한경(한국경제 잡지 자회사, 대학 취업·창업 섹션)
- **출처 유형**: 언론(대학생·청년 창업 소개 특화 매거진 — 전통 경제 일간지 기사가
  아닌, 대학 예비창업패키지 선정기업을 소개하는 커리어 매거진 코너)
- **출처 URL**: https://magazine.hankyung.com/job-joy/amp/202603152392d
- **확인일**: 2026-08-14
- **재조사 1차 (B형 해소 — "200만원 결제 시 삼성카드 100만원+현대카드 100만원" 구체 금액
  예시)**: 원 출처(magazine.hankyung.com/job-joy/amp/202603152392d)를 두 차례 독립적으로
  재접속해 재확인한 결과 다음 문장을 동일하게 확인: "예를 들어 온라인 쇼핑몰에서 200만원짜리
  노트북을 살 때, 소비자가 가진 삼성카드로 100만원, 현대카드로 100만원을 나누는 결제 방식이다."
  (동일 URL, 처음 조사 시 발췌 목록에서 누락됐던 문장을 재확인으로 발견). 확인일: 2026-08-14
- **화제성 근거**: 이 기사 외에 다른 매체·커뮤니티에서 페이랩/리틀핀을 다룬 후속
  보도나 게시물을 찾지 못했다. **화제성 근거는 사실상 없음 — 커뮤니티·SNS 반응,
  후속 보도 모두 확인되지 않았고, 서비스 자체도 아직 정식 출시 전(2027년 예정)
  단계다.** 참신한 결제 메커니즘(다중 카드 결합결제) 자체의 아이디어 가치만을 보고
  참고용으로 기록하며, report-writer/fact-checker가 채택 여부를 이 caveat을 감안해
  별도 판단할 것을 권고한다(scope.md 기준상 "검증 안 된 파일럿도 OK"에는 해당하나,
  "실제 반응의 온도"라는 화제성 기준은 명백히 미충족).
- **카카오페이 시도 아이디어**: 카카오페이머니/포인트와 제휴 신용카드를 하나의
  결제 트랜잭션에서 분할 사용하는 기능은, 카카오페이가 이미 보유한 "여러 결제수단
  연결" 인프라 위에 UX만 추가하면 되는 확장이다. 특히 카카오페이 제휴카드 실적 조건
  달성을 유도하는 리워드 마케팅과 결합하면, 카드사 제휴 마케팅 예산을 결제 UX
  자체의 차별화 요소로 전환할 수 있는 아이디어.

### 확대조사 중 검토했으나 미채택한 추가 후보 (비언론 채널 확대조사분)

- **비피엠지×웰컴페이먼츠×브이디크럭스 스테이블코인 커피결제 제휴** (2026-05-08,
  ZDNet Korea): 컴포즈커피·하삼동커피 프랜차이즈를 통해 스테이블코인 결제 사업화를
  공동 추진하는 제휴 발표. 기업 규모는 중소형사 연합이라 "대형 제도권" 배제 기준에는
  해당하지 않으나, 메커니즘 자체(스테이블코인 QR 오프라인 결제)가 이미 위 "구 버전"
  섹션에 채택된 KB금융×할리스 사례와 본질적으로 동일해 "참신한 조합"으로 보기 어렵고,
  기사 시점 기준 실제 매장 실증이 아닌 "제휴 체결" 발표 단계라 미채택.
- **젝토(ZEKTO)×비댁스×엘케이벤처스 '인생네컷' 스테이블코인 결제 실증**: 셀프
  포토부스 매장에서 원화 스테이블코인(KRW1)으로 결제하는 실증으로 소규모 스타트업
  주도 사례라 참신성은 있으나, 보도 시점이 2026년 8월 10~11일로 조사기간(~06-30)
  밖이라 미채택.
- **루트파인더즈 TTP 관련, 순수 비언론(개인 블로그·커뮤니티·SNS) 원문**: 브런치·
  velog·디스콰이엇·GeekNews·OKKY·더쿠·인스티즈·에펨코리아·클리앙·X(트위터)에서
  "루트파인더즈", "Talk To Pay", "TTP 결제" 등으로 검색했으나 관련 개인 게시물을
  찾지 못함 — 벤처스퀘어·소셜밸류 등 스타트업 전문 매체 보도만 확인됨.
- **와디즈 결제 관련 웨어러블(반지·팔찌) 크라우드펀딩**: "결제", "반지", "팔찌",
  "웨어러블" 키워드로 다수 검색했으나 국내 결제 기능 탑재 웨어러블의 2026년 상반기
  신규 펀딩 프로젝트를 찾지 못함. 참고로 유사 제품군(온블리프 'NFC 교통카드 반지')은
  발견했으나 팝업스토어·언론보도 시점이 2025년 6월로 조사기간 밖이라 제외.
- **제주 전국체전 NFT 디지털 티켓×지역화폐 연계** (2026-06-14, 뉴시스 등): 경기장
  방문 인증 시 지역화폐를 지급하는 방식으로 참신하나, 지방자치단체 주도의 대형
  공공행사 티켓팅·리워드 시스템이라 "결제" 자체의 메커니즘 혁신이라기보다 인증기반
  리워드 지급에 가까워 오프라인 "결제" 세그먼트 부합성이 낮고, 지자체 주도 대형
  사업이라는 점에서도 스타트업/개인 단위 참신한 시도라는 이번 조사 취지와 거리가
  있어 미채택.
- 그 외 시도한 비언론 채널 검색(빈손): 손바닥/정맥 결제 신규 도입, 안면인식 결제
  신규 스타트업, NFC 반지 신규 스타트업, 무인매장 이색 결제, AI 에이전트 자동결제
  오프라인 키오스크(넥스트페이먼츠 'AI 점장' — 서비스는 실재하나 2026년 상반기
  출시·공개 시점을 특정할 원문을 찾지 못해 미채택), 1인 개발 결제 토이프로젝트,
  대학생 결제 아이디어 공모전 수상작, 해커톤 결제 부문 수상작(2026년 블록체인 AI
  해커톤은 모바일 신분증·STO 위주로 오프라인 결제 관련 수상작 확인 안 됨), VC
  시드투자 결제 스타트업(리틀핀 외 확인 안 됨).

### 미채택 사유 (탐색했으나 채택하지 않은 후보 및 검색 시도 기록)

- **탐색 범위**: (1) 스타트업 전문 미디어(플래텀, 아웃스탠딩, 바이라인네트워크,
  핀테크투데이) 검색, (2) 소상공인 커뮤니티(아프니까 사장이다) 화제 검색, (3)
  크라우드펀딩(와디즈) 신박한 결제 굿즈 검색, (4) 웨어러블(반지·목걸이) 국내 스타트업
  검색, (5) 손바닥 정맥 결제, 음성 결제, 무인매장 정직상점 QR결제 등 폼팩터·메커니즘
  기준 검색, (6) 탄소중립 리워드·지역화폐×NFT 결합 검색, (7) 반려동물 결제카드 검색,
  (8) 서빙로봇×결제 통합 검색, (9) 핀테크 아이디어 공모전(2026년 8월 접수 시작,
  아직 수상작 없음) 확인, (10) 더쿠·인스티즈 등 커뮤니티 화제 검색. 총 20회 이상의
  개별 검색을 시도함. 확인일: 2026-08-14
- **쿠팡×우리은행 원화 스테이블코인 실시간 정산 PoC**: "결제-실시간정산-온/오프램프"를
  상용환경과 동일하게 검증한 국내 최초 사례로 참신성은 있으나, (a) 발표일이 2026년
  7월 27일로 조사기간(~06-30) 밖이고, (b) 실제 시나리오도 쿠팡이츠 "배달 주문 결제"의
  가맹점 정산 구조 검증이라 오프라인(대면) 결제 세그먼트와 직접 맞지 않아 미채택.
  참고: 한국경제 https://www.hankyung.com/article/202607277302B (확인일 2026-08-14)
- **토스페이먼츠 예금토큰 결제 인프라 구축(CBDC 민간 실증사업)**: "카드 대신 예금토큰
  결제"라는 프레이밍은 흥미로우나, (a) 보도 시점이 2026년 7월 22~31일로 조사기간 밖이고,
  (b) 정부(과기정통부·금융결제원) 주도 컨소시엄형 실증사업으로 소규모 실험이라기보다
  기존 KB금융 스테이블코인 PoC(구 버전 국내-4)와 유형이 유사한 "제도권 대형 PoC"에
  가까워 미채택. 참고: 뉴스핌 https://www.newspim.com/news/view/20260722001103 (확인일
  2026-08-14)
- **전국 골목상권 표준QR 해외페이 연동 확대(한국관광공사)**: 소상공인이 저비용 QR
  키트만으로 22개국 71개 해외 간편결제를 받을 수 있게 됐다는 점은 흥미로우나, 이는
  scope.md가 명시적으로 배제 대상으로 규정한 "기존 서비스의 가맹점/지역 단순 확장"에
  해당해(표준QR 인프라 자체는 기존 서비스이고 이번 건은 지역 확산일 뿐) 미채택. 참고:
  전자신문 https://www.etnews.com/20260526000356 (확인일 2026-08-14)
- 그 외 손바닥 정맥 결제(후지쯔, 국내 신규성 부족 — 2017년부터 진행 중인 기존 기술),
  서빙로봇×결제 통합(구체적 신규 사례 미발견), 지역화폐×NFT 결합(구체적 국내 사례
  미발견), 반려동물 결제카드(우리카드 기존 상품 외 신규 참신 사례 미발견) 등은 검색
  결과 자체가 빈약하거나 기존 상품의 재탕 수준이라 evidence 항목화하지 않음.

## 채택하지 않은 항목 (조사했으나 국내 카탈로그에서 제외)

- **쿠팡페이 오프라인 결제 진출('로켓페이')**: 2026년 5월 13일 머니투데이가 "쿠팡페이가
  채널전략·파트너십 인력을 채용 중"이라고 단독 보도했으나, 당시 쿠팡페이는 "외부 간편결제 시장
  진출 여부는 확인이 어렵다"는 공식 입장이었다 (인력 채용설 수준, 공식 서비스 발표 아님). 실제
  '로켓페이' 공식 출시 발표는 2026년 7월 10일로 조사기간(2026-01-01~06-30) 이후이므로 국내
  카탈로그에는 채택하지 않음. (참고: 머니투데이,
  https://www.mt.co.kr/living/2026/05/13/2026051316334240505 / 아시아경제,
  https://www.asiae.co.kr/article/2026071009273661800 — 확인일 2026-08-14)
- **토스원 신한카드(페이스페이 전용 카드) 출시**: 2026년 7월 2일 출시로 조사기간(~06-30) 이후
  발생. 확인일 2026-08-14 기준 출처: 뉴스핌 https://www.newspim.com/news/view/20260702000108
- **토스 '페이스페이' 서비스 자체**: 2025년 9월 정식 출시로 조사기간(2026 상반기) 이전부터
  존재하는 서비스이며, 2026년 상반기 중 확인된 것은 가입절차 간소화·가맹점 확대 등 점진적
  업데이트 수준이라 "처음 공개/출시/화제화" 기준에 부합하는 새 항목으로 채택하지 않음.
  **[재조사 1차, A형 해소]** 처음 조사 시 출처 URL이 누락되어 있었음. 재조사로 아래 2건의
  출처를 신규 확보함.
  - 바이라인네트워크(byline.network), 2025-09-02 발행, "토스, 연말 토스페이 수백만명
    목표…새 단말기 프로모션은 비공개": "토스는 이날 간담회에서 페이스페이 정식 출시를
    알리며" (간담회 개최일=기사 발행일인 2025년 9월 2일). 출처 URL:
    https://byline.network/2025/09/0902-4/
  - 데일리포스트(thedailypost.kr), "토스 '페이스페이', 가입자 200만명 돌파…심리적 장벽 어떻게
    뚫었나?": "2일 서울 강남구 복합문화공간 에스제이쿤스트할레에서 열린 페이스페이 정식 출시
    기자간담회"라고 명시해 2025년 9월 2일 정식 출시를 직접 확인. 출처 URL:
    https://www.thedailypost.kr/news/articleView.html?idxno=112950
  - 확인일: 2026-08-14 (두 출처 모두 "2025년 9월 2일 정식 출시"를 일치되게 뒷받침하며, 조사
    시점(2026 상반기 이전) 판단은 기존 결론과 동일하게 유지됨)
- **신한카드 × 마스터카드 'AI 에이전트 페이' 실거래(2026년 3월 30일)**: 국내 카드업계 최초의
  AI 에이전트 자동결제 실증 사례이나, 보도 내용상 "글로벌 모빌리티 서비스 예약·결제" 연동으로
  온라인/앱 내 자동결제 성격이 강해 오프라인(대면) 결제 카탈로그 기준에 명확히 부합하는지
  확인되지 않아 이번 국내 오프라인 결제 카탈로그에서는 제외함 (확인일 2026-08-14, 출처:
  아주경제 https://www.ajunews.com/view/20260330100524938 ). 필요 시 별도 세그먼트(예:
  카드중개)에서 재검토 권장.
