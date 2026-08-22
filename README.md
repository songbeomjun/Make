# VoxelCraft Standalone v3

GitHub Pages의 지속적인 검은 화면 문제를 구조적으로 제거하기 위해 새로 만든 단일 HTML 버전입니다.

## 변경점
- Three.js 완전 제거
- 외부 CDN 의존성 0
- 32×32 블록 텍스처를 HTML 내부에 직접 포함
- 페이지를 열 때는 WebGL을 초기화하지 않음
- 순수 HTML/CSS 시작 화면을 먼저 표시
- 플레이 버튼을 누른 뒤에만 자체 WebGL 1 엔진 시작
- WebGL/셰이더/텍스처 실패 시 검은 화면 대신 오류 내용 표시
- 청크 메시, 절차적 지형, 동굴, 광석, 나무, 물, 블록 채굴/설치, 저장, 모바일 터치 조작 포함

## GitHub Pages 적용
기존 저장소의 예전 `index.html`을 삭제하고 이 버전의 `index.html` 하나를 저장소 최상위(root)에 업로드하세요.

Settings → Pages → Deploy from a branch → main / (root)

Pages 주소에서 처음부터 `HTML 정상 로드됨`이 보이면 GitHub 배포는 정상입니다.
