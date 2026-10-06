# 집현전의 암호 · 한글날 방탈출

초등 중·고학년을 위한 한글날 방탈출 웹 게임입니다. 빌드 과정이 없는 단일 HTML 파일(`index.html`)이라 어디서든 바로 열립니다.

## 파일 구성

- `index.html` : 게임 본체 (HTML, CSS, JS 한 파일)
- `netlify.toml` : Netlify 배포 설정
- `README.md` : 이 안내 문서

## 배포 방법 1: GitHub + Netlify (수정할 때마다 자동 반영)

1. GitHub에서 새 저장소(Repository)를 만듭니다. (예: `hangul-escape-room`)
2. 저장소의 **Add file → Upload files**로 이 폴더의 파일 3개를 올리고 **Commit changes**를 누릅니다.
3. Netlify에 로그인해 **Add new site → Import an existing project**를 선택하고 GitHub 저장소를 연결합니다.
4. 빌드 명령은 비워 두고, 배포 폴더(Publish directory)는 `.` 그대로 둔 채 **Deploy**를 누릅니다.
5. 배포가 끝나면 `https://사이트이름.netlify.app` 주소가 생깁니다. 이 주소를 학생들에게 나눠 주면 로그인 없이 바로 접속됩니다.
6. 이후 GitHub의 `index.html`을 수정해 커밋하면 같은 주소에 자동으로 반영됩니다.

사이트 이름은 Netlify의 **Site configuration → Change site name**에서 바꿀 수 있습니다.

## 배포 방법 2: Netlify에 바로 끌어다 놓기 (GitHub 없이)

1. Netlify의 **Add new site → Deploy manually** 화면을 엽니다.
2. 이 폴더(또는 함께 드린 zip 파일)를 화면에 끌어다 놓습니다.
3. 바로 주소가 생성됩니다. 내용을 고친 뒤에는 같은 사이트의 **Deploys** 탭에서 다시 끌어다 놓으면 업데이트됩니다.

## 수업 전 확인

- 로그인하지 않은 브라우저(시크릿 창)에서 주소를 열어 끝까지 한 번 풀어 보세요.
- 글꼴은 Google Fonts에서 불러옵니다. 학교 네트워크에서 차단되면 기본 글꼴로 바뀌지만 게임은 정상 작동합니다.
