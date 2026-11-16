# PRISM · DP/PSI Platform Demo

수요계획(DP) 플랫폼 PRISM(Planning · Run-rate · Inventory · Supply)의 화면 시연용 정적 데모입니다.

- `index.html`은 암호화되어 있으며, 접속 시 비밀번호를 입력해야 열립니다 (AES-GCM, PBKDF2 키 유도, 브라우저 내 복호화).
- 데모 데이터는 마스킹되어 있습니다: SKU·시리즈·거래선·창고명은 가명, 수량은 SKU별 임의 배수 적용, 프로젝트는 가상 데이터.
- 입력·결정 기능은 브라우저 세션 안에서만 동작하며 저장되지 않습니다.
