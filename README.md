# ExplosionOps Preview

H.QUANT의 **ExplosionOps 동료 검토용 공개 대시보드**입니다.

## 미리보기

- GitHub Pages: https://h-quant.github.io/explosion-ops-preview/
- 피드백 Issue: https://github.com/H-QUANT/explosion-ops-preview/issues/1

## Preview v2

이번 버전은 원래 구현된 Evidence-first MVP의 화면 구성을 공개 프리뷰에 최대한 동일하게 반영했습니다.

- Command Center, Today, Instruments, Prediction vs Actual, Performance, Calendar, Model Lab, Data Health, GitHub, NOVA AI, Approvals, Settings
- `Han Secretary`를 **NOVA AI · Market Intelligence Copilot**으로 리브랜딩
- GitHub 공식 마크 형태의 아이콘 적용
- 데스크톱 좌측 패널 접기/펼치기 및 상태 기억
- 오늘 추천 Top 5 행을 클릭하면 해당 종목의 Instruments 상세 화면으로 이동
- 반응형 로그인 화면과 로그아웃 제공
- 동료 피드백 Issue 연결

## 동료 검토용 로그인

```text
Email: reviewer@h-quant.ai
Access code: NOVA-2026
```

로그인 화면의 **데모 계정 채우기**를 누르면 위 값이 자동 입력됩니다.

> 이 로그인은 공개 GitHub Pages에서 제품 흐름을 검토하기 위한 **클라이언트 측 UX 게이트**입니다. 공개 저장소의 파일과 데모 데이터에 대한 보안 경계가 아니며, 실제 서비스 로그인은 서버 세션과 SSO/OAuth, RBAC로 별도 구현해야 합니다.

## 검토 목적

ExplosionOps는 한국 주식의 장전 급등 후보를 탐색하고, 예측 당시 근거를 동결하며, 개장 후 실제 성과를 검증하고, 실패 원인을 반복 학습하는 자율형 시장 연구 운영 플랫폼입니다.

이 저장소에는 동료 검토용 정적 UI와 데모 데이터만 포함됩니다. 실제 운영 코드, 비공개 설정, API 키, 계좌정보, 실시간 시장 데이터는 포함하지 않습니다.

## 중요 안내

- 화면 데이터는 `DEMO REPLAY · NOT LIVE DATA`입니다.
- 투자 권유나 수익 보장이 아닙니다.
- 검색엔진 수집을 제한하도록 설정했지만, 공개 저장소와 공개 Pages의 콘텐츠는 누구나 접근할 수 있습니다.
- 비밀번호, API 키, 계좌정보, 고객정보 또는 비공개 데이터를 피드백에 작성하지 마세요.

## 피드백 중점 항목

1. 첫 화면에서 30초 안에 오늘의 추천·위험·데이터 상태가 이해되는가?
2. Explosion Probability와 Tradeability의 차이가 명확한가?
3. 예측 대 실제 결과 및 놓친 종목의 원인이 이해되는가?
4. 날짜별 데이터, 모델 버전, 학습 상태를 찾기 쉬운가?
5. NOVA AI 채팅과 승인 흐름이 신뢰감을 주는가?
6. 로그인부터 종목 상세 조회까지의 흐름이 자연스러운가?
7. 불필요하거나 부족한 화면과 정보는 무엇인가?

---

Copyright © H.QUANT. 동료 검토용 프리뷰입니다.
