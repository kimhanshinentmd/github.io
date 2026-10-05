# 김한신 홈페이지

## 폴더 구조
- `_config.yml` : 사이트 이름, 주소 등 기본 설정
- `_layouts/` : 모든 페이지의 공통 틀 (손대지 않아도 됩니다)
- `index.md` : 첫 화면
- `about.md` : 소개 페이지
- `dizziness/` : 어지럼 글 모음 (글 하나가 파일 하나)
- `assets/images/` : 그림과 사진
- `robots.txt` : 검색봇·AI 접근 허용 설정

## GitHub에 올리는 순서
1. GitHub에서 저장소(Repository)를 만듭니다. 이름은 `깃허브아이디.github.io`, 공개(Public)로 설정합니다.
2. 이 폴더의 파일 전체를 저장소에 업로드합니다. (웹에서 Add file → Upload files)
3. 저장소 Settings → Pages에서 Branch를 `main`, 폴더를 `/ (root)`로 선택하고 저장합니다.
4. 1~3분 뒤 `https://깃허브아이디.github.io` 에서 확인합니다.
5. `_config.yml`의 `url`과 `robots.txt`의 주소를 실제 주소로 고칩니다.

## 도메인 연결 후
저장소 최상단에 `CNAME` 파일을 만들고 도메인 주소 한 줄(예: `example.com`)만 적습니다. 그 뒤 `_config.yml`의 `url`과 `robots.txt`의 주소를 도메인으로 바꿉니다.

## 새 글 추가
`dizziness/` 폴더의 파일 하나를 복사해서 이름과 내용을 바꾸고, `dizziness/index.md`에 링크를 추가합니다.
