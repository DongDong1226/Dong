# 모임회비 현황

카카오뱅크 모임통장 회비 납부현황 페이지 (모바일용, 파일 하나: `index.html`)

## GitHub Pages 배포
1. GitHub에서 새 저장소 만들기 (예: `moim-dues`)
2. 이 폴더의 파일(`index.html`, `.nojekyll`, `README.md`) 올리기
3. 저장소 **Settings → Pages → Branch: `main` / `/ (root)` → Save**
4. 1~2분 뒤 `https://<깃허브아이디>.github.io/moim-dues/` 에서 열림

## 매달 갱신
새 거래내역을 Claude에게 주면 `index.html`을 다시 만들어 줍니다. 덮어쓰고 커밋하면 페이지가 자동으로 바뀝니다.

> 저장소가 공개(public)이면 페이지도 누구나 볼 수 있습니다 (모임원 이름, 납부현황, 계좌번호 포함).
