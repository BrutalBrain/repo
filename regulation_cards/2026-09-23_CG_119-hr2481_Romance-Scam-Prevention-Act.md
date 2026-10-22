# Romance Scam Prevention Act

> 🇺🇸 미 의회 (U.S. Congress) · Public Law · 공포 2026-09-23 · 카드 2026-10-23
> 원문: https://www.congress.gov/bill/119th-congress/house-bill/2481

## 💡 한 줄 결론

미 데이팅 플랫폼에 사기계정 통지 의무(24시간 내)를 부과하는 연방법 — 플랫폼 준수비용은 소폭 늘고 사기탐지·알림 솔루션에 수요가 생기나, 안전항·연방 단일기준으로 규제 파편화 리스크는 오히려 정리되는 저강도 규제.

**파급 유형**: 준수비용 증가 · 수요 창출

## 승자와 패자

| 산업 | 방향 | 강도 | 근거 | 원문검증 |
|---|---|---|---|:-:|
| 사기탐지·신원인증 소프트웨어(트러스트&세이프티 솔루션) | 🟢 수혜 | 중 | 법이 '사기 위험이 유의미한 회원'을 플랫폼 스스로 판정해 계정을 정지·해지하고 이를 근거로 통지하도록 요구하므로, 데이팅 플랫폼은 사기계정 탐지·판정 체계를 갖춰야 한다. 이 판정 역량을 외주·공급하는 사기탐지, 본인확인(KYC류), 리스크 스코어링 벤더의 수요가 늘어난다. | ✓ |
| 메시징·알림 인프라(이메일·SMS 발송 서비스) | 🟢 수혜 | 약 | 통지는 이메일 또는 문자메시지 등으로 24시간~3일 내에 의무 발송해야 하므로, 대량 트랜잭셔널 메시징(이메일/SMS API) 사업자에게 소폭의 추가 발송 수요가 생긴다. | ✓ |
| 온라인 데이팅 플랫폼(매칭 앱·웹 서비스) | 🔴 피해 | 중 | 사기계정으로 판정해 차단(fraud ban)한 회원과 메시지를 주고받은 모든 회원에게 24시간(예외 시 3일) 내 소정 내용을 담은 통지를 의무적으로 보내야 하며, 위반 시 FTC의 불공정·기만행위(UDAP) 위반으로 제재받고 주 법무장관도 민사소송을 제기할 수 있다. 탐지·판정·통지 시스템 구축과 운영이 전부 플랫폼 부담이다. 다만 안전항(safe harbor)과 연방 단일기준(주법 선점)은 소송·규제 파편화 리스크를 줄여 부담을 일부 상쇄한다. | ✓ |

## 크기 (문서 내 추정치만)

_문서에 비용·편익 추정치 없음 (추정하지 않음)_

## 타임라인 · 확정성

- 시행일: 2027-09-23 · 단계적용: 공포(2026-09-23) 후 1년 유예 — 시행일부터 통지 의무 전면 적용, 단계적 적용 구간 없음
- 실적 반영 추정: 2027-Q4
- 단계: 채택 · 확정 가능성 **높음** — 상·하원 통과 후 등록(Enrolled)된 Public Law로 2026-09-23 공포 완료. 시행일이 법문에 '제정일로부터 1년 후'로 고정돼 있어 별도 하위 규정 없이도 2027-09-23 자동 발효된다.

## 파급 사슬

- 데이팅 플랫폼에 사기계정 탐지·통지 의무 부과 → 플랫폼의 트러스트&세이프티 투자 확대 → 사기탐지·신원인증 솔루션 및 이메일·SMS 발송 인프라 매출 증가
- 통지 의무·FTC 제재 리스크 → 소형 데이팅 서비스의 컴플라이언스 고정비 부담 상대적 증가 → 탐지 체계를 이미 갖춘 대형 플랫폼으로의 점유 집중 가능성

## 무효화 리스크

- 의회의 후속 수정입법 또는 폐지(이미 공포된 법률이라 가능성 낮음)
- FTC의 집행 우선순위·리소스에 따라 실질 집행 강도가 약화될 가능성
- 주법 선점 조항(One National Standard)의 범위를 둘러싼 주정부와의 소송으로 일부 조항 해석이 흔들릴 가능성
- '사기 위험의 유의미성' 판정이 플랫폼 재량(in the judgment of the provider)이라 보수적 운영으로 통지 건수 자체가 적어져 실효·파급이 축소될 가능성

## 관찰 체크포인트

- **2026-Q4 ~ 2027-Q3 (시행일 전)** — FTC의 집행 가이던스·해석 자료 또는 관련 규정(regulation promulgated under this section) 공표 여부
- **2027년 상반기 실적 발표** — 매치그룹·범블 등 주요 데이팅 플랫폼의 컴플라이언스 대응(통지 시스템 구축, 비용 가이던스 언급) 공시·실적 콜 코멘트
- **2027-09-23 이후 ~ 2028-Q1** — 시행일 도래 및 FTC·주 법무장관의 첫 집행(민사소송) 사례

---

## 세부사항

**핵심 조항**

- 사기 차단 통지 의무 — 차단된 회원과 메시지를 교환한 회원에게 통지 제공 ✓
  > "An online dating service provider shall provide to a member of the online dating service a fraud ban notification if the member has received a message through the online dating service from a banned member of the online dating service."
- 통지 시한 — 원칙 24시간 이내(운영사 판단 지연 시 3일, 수사기관 요청 시 추가 지연 가능) ✓
  > "an online dating service provider shall provide a fraud ban notification under paragraph (1) not later than 24 hours after the fraud ban is initiated against the banned member."
- 안전항 — 통지 의무 이행 행위에 대해 회원·차단회원·전 회원의 청구로부터 면책 ✓
  > "An online dating service provider is not liable to a member, a banned member, or a former member for a claim based on an online dating service provider's action to comply with the requirements for providing a fraud ban notification under this subsection."
- FTC 집행 — 위반은 FTC법상 불공정·기만행위 규칙 위반으로 취급 ✓
  > "A violation of this section or a regulation promulgated under this section shall be treated as a violation of a rule defining an unfair or deceptive act or practice under section 18(a)(1)(B) of the Federal Trade Commission Act (15 U.S.C. 57a(a)(1)(B))."
- 주 법무장관의 민사소송 권한 — 주민 보호를 위해 연방지방법원에 제소 가능(FTC 사전 통지 의무) ✓
  > "the attorney general of the State may, as parens patriae, bring a civil action on behalf of the residents of the State in an appropriate district court of the United States to obtain appropriate relief."
- 연방 단일기준 — 주·지방정부의 상이한 통지 규제 금지(계약·불법행위 주법은 예외) ✓
  > "that requires an online dating service provider to notify, prohibits an online dating service provider from notifying, or otherwise affects the manner in which an online dating service provider is required or permitted to notify, a member of the online dating service"
- 시행일 — 제정일로부터 1년 후 발효 ✓
  > "This section shall take effect on the date that is 1 year after the date of the enactment of this Act."

**적용 대상·예외**: 적용 대상: 웹사이트·모바일 앱으로 회원 간 데이트·로맨틱 관계의 사회적 소개를 주선·촉진하는 '온라인 데이팅 서비스'를 영업으로 제공하는 자(online dating service provider). 지역: 미국 전역 — '주'에 50개 주, 컬럼비아특별구, 커먼웰스·준주·속령, 연방 인정 인디언 부족까지 포함. 규모 기준이나 소규모 사업자 면제 조항은 없음. 예외: 수사기관 요청 시 통지 지연 허용, 계약·불법행위 관련 주법은 연방 선점에서 제외.

**제정 배경**: 법문 자체에는 상세한 제정 경위 서술이 없고, 법의 목적이 전문(前文)에 '온라인 데이팅 서비스 제공자가 회원에게 사기 차단 통지를 제공하도록 요구하기 위함(To require online dating service providers to provide fraud ban notifications to online dating service members, and for other purposes)'으로 명시돼 있다. 제119대 의회 제2회기(2026년)에 H.R. 2481로 통과돼 2026-09-23 공포됐다.

**판단 논거**: 비용 부담의 중심은 (a)항의 통지 의무와 (b)항의 FTC·주 법무장관 이중 집행 구조로, 데이팅 플랫폼이 사기계정을 탐지·판정하고 교신 이력을 역추적해 24시간 내 통지하는 시스템을 구축·운영해야 하므로 플랫폼이 유일한 직접 losers다. 그 비용이 수입으로 흘러가는 쪽은 두 갈래다: (d)(3)의 fraud ban 정의가 '운영사의 판단으로 사기 위험이 유의미한 회원'을 전제하므로 판정 역량, 즉 사기탐지·리스크 스코어링 솔루션 수요가 생기고(winners 1), (a)(3)(A)가 통지 수단을 이메일·문자메시지로 지정하므로 트랜잭셔널 메시징 인프라에 발송 수요가 생긴다(winners 2). 다만 본문에 비용 추정치가 전혀 없고 통지 자체는 기술적으로 단순해 파급 강도는 medium~weak 수준이다. 한편 (a)(4) 안전항과 (c) 연방 단일기준은 플랫폼의 소송 리스크와 주별 규제 파편화를 제거해 부담을 상쇄하는 방향으로 작용하며, 이미 탐지 체계를 갖춘 대형 플랫폼일수록 한계 준수비용이 낮아 상대적으로 유리하다.

## 📖 법안 요약 (쉬운 설명)

온라인 데이팅 서비스(웹사이트·모바일 앱) 운영사에 '사기 차단 통지' 의무를 부과하는 미국 연방법이다. 운영사가 어떤 회원을 사기 위험이 크다고 판단해 계정을 정지·해지(fraud ban)하면, 그 회원과 메시지를 주고받은 다른 회원들에게 원칙적으로 24시간 안에(운영사 판단으로 지연 시 3일, 수사기관 요청 시 그 이후) 통지를 보내야 한다. 통지에는 차단된 회원의 아이디, 마지막 교신 시점, 사기 시도 가능성 안내, 현금·금융정보를 보내지 말라는 경고, 사기 예방 수칙, 고객센터 연락처가 들어가야 하며 이메일·문자 등으로 명확하게 전달해야 한다. 통지 의무를 이행한 운영사는 그로 인한 손해배상 청구로부터 면책된다(안전항). 위반은 연방거래위원회(FTC)법상 불공정·기만행위 위반으로 취급돼 FTC가 제재하고, 주 법무장관도 주민을 대리해 연방법원에 민사소송을 낼 수 있다. 주(州)나 지방정부는 이와 다른 자체 통지 규정을 둘 수 없는 연방 단일기준이 적용되며, 다만 계약·불법행위 관련 주법은 유지된다. 법은 제정일(2026-09-23)로부터 1년 뒤 시행된다.

---

_생성: sector_chain 규제 영향 카드 · 모델 claude-fable-5,claude-haiku-4-5-20251001 · 인용 기계검증 통과_
