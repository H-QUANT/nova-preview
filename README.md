# H-QUANT NOVA Preview

**H-QUANT NOVA**의 동료 검토용 공개 대시보드입니다.

- Product: **H-QUANT NOVA**
- AI experience: **NOVA AI · Market Copilot**
- Quant model family: **ExplosionScore**
- Public Pages: https://h-quant.github.io/nova-preview/
- Feedback: https://github.com/H-QUANT/nova-preview/issues/1

## Preview scope

현재 프리뷰는 장전 후보 탐색, Prediction Snapshot, 첫 1시간 검증, 예측 대 실제 비교, 날짜별 Research Ledger, Model Lab, Data Health, GitHub 로그, NOVA AI 채팅과 승인 흐름을 동료가 검토할 수 있도록 구성합니다.

- 전체 MVP 화면 구조
- 데스크톱 좌측 패널 접기/펼치기와 상태 기억
- 추천 Top 5 선택 시 종목 상세 화면 이동
- NOVA AI 브랜딩과 GitHub 공식 마크
- 반응형 로그인·로그아웃 흐름
- 날짜별 NOVA Research Ledger 조회

## NOVA Research Ledger

공개 가능한 사후 연구 데이터는 날짜별 compact JSON으로 게시합니다.

```text
data/index.json
data/YYYY/MM/DD/dashboard.json
data/YYYY/MM/DD/manifest.json
```

장전 원본 예측과 내부 근거는 비공개 원본 저장소에 보존하고, 공개 저장소에는 장 종료 후 정제된 projection만 게시합니다. 데이터가 없거나 불완전한 단계는 추정하지 않고 그대로 표시합니다.

## Preview login

이 로그인은 공개 Pages의 제품 흐름을 검토하기 위한 **클라이언트 측 UX 게이트**입니다. 실제 보안 경계가 아니며, 정식 서비스에서는 OIDC/SSO와 RBAC로 교체합니다.

## Important

- 화면 데이터는 `RESEARCH PREVIEW · NOT LIVE TRADING`입니다.
- 투자 권유 또는 수익 보장이 아닙니다.
- 실제 운영 코드, API Key, 계좌정보, 비공개 시장 데이터와 라이선스 원문은 포함하지 않습니다.
- 공개 저장소와 Pages의 콘텐츠는 누구나 접근할 수 있습니다.

## Review focus

1. 첫 화면에서 추천·위험·데이터 상태를 빠르게 이해할 수 있는가?
2. Explosion Probability와 Tradeability의 차이가 명확한가?
3. 예측 대 실제 결과 및 놓친 종목의 원인이 이해되는가?
4. 날짜별 Snapshot·평가·학습 상태를 찾기 쉬운가?
5. NOVA AI와 승인 흐름이 신뢰감을 주는가?
6. 로그인부터 종목 상세 조회까지 자연스러운가?

---

Copyright © H-QUANT. Public research preview.