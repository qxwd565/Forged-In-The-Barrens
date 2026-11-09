# Forged-In-The-Barrens

HSdeck schema 1 카드 API. 한국 날짜(Asia/Seoul)를 사용합니다. `data/<cardID>.json`의 `card`에는 카드가 처음 사용 가능해진 시점의 스펙을, `card.patches`에는 이후 실제 변경된 필드만 기록합니다.

- `cards.json` 현재 스펙 및 기존 원화 경로 보존
- `render.json` 현재 스펙 + 과거 날짜별 변경값
- `history.json` 구버전 플러그인 호환
- `release-policy.json` 본 확장팩 및 통곡의 동굴 미니 세트 날짜
- `data/combinations/` 카자쿠스 골렘 108개 조합 변형(카드 ID 중복 등록 방지)

최초 스펙은 공식 변경 기록으로 확인한 필드 이외에는 최신 스냅샷으로 잠정 기록되어 있으며, 상태는 `card.initialSpecStatus`에 표기됩니다. **기존 원화·황금 애니메이션은 수정하지 않았습니다.**
