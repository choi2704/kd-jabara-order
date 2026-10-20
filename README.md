# 강동자바라 차양 제작 견적기 (v1.3)

GitHub Pages로 배포할 수 있도록 준비한 정적 웹페이지입니다.

## GitHub에 올리는 방법
1. GitHub에서 새 저장소(Repository)를 만듭니다. (공개 웹사이트로 배포하려면 Public 권장)
2. 이 ZIP의 압축을 풀고 **안의 파일들**(`index.html`, `.nojekyll`, `README.md`)을 저장소 최상위(root)에 업로드하고 커밋합니다. ZIP 파일 자체만 업로드하면 사이트가 열리지 않습니다.
3. 저장소의 **Settings → Pages**에서 **Build and deployment → Deploy from a branch**를 선택합니다.
4. Branch는 `main`, Folder는 `/(root)`를 선택한 뒤 저장합니다.
5. 몇 분 뒤 Pages에 표시된 사이트 주소에서 견적기를 열 수 있습니다.

## 참고
- 견적기의 **파일 저장** 기능으로 견적 목록/단가를 JSON으로 따로 백업해 두세요.
- 브라우저의 자동 저장 데이터(localStorage)는 컴퓨터·브라우저·사이트 주소별로 따로 보관됩니다. 기존 HTML 파일에서 사용한 저장 내용이 GitHub Pages 사이트로 자동 이전되지는 않습니다. 기존 화면에서 **파일 저장**, 새 사이트에서 **불러오기**를 사용해 옮길 수 있습니다.
- 이 파일은 강동자바라 차양 견적기 v1.3 원본 HTML을 `index.html`로 구성한 것입니다.
