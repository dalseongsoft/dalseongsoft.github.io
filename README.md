# 달성소프트 웹사이트

달성소프트(DALSEONG SOFT) 소개 정적 사이트. Google Play 조직 계정 인증, 앱 개인정보처리방침,
AdMob app-ads.txt 용도.

- 저장소: https://github.com/dalseongsoft/dalseongsoft.github.io (GitHub 계정 dalseongsoft, 구글 dalseongsoft@gmail.com 로그인)
- 주소: https://dalseongsoft.github.io/
- 개인정보처리방침: https://dalseongsoft.github.io/privacy/ (영어: https://dalseongsoft.github.io/privacy/#en)
- 배포: main 브랜치 루트에서 GitHub Pages 자동 배포 (2026-10-12 공개)

## 구성

```
index.html          홈 (한국어): 소개 · 앱 · 사업자 정보 · 문의
en/index.html       홈 (영어)
privacy/index.html  개인정보처리방침 (한국어 #ko + 영어 #en), 모든 앱 공통
404.html
assets/css/style.css
assets/img/favicon.svg
```

## 업데이트 방법

- 이 PC의 git 자격증명은 devk770319-ui 계정용이라 이 저장소에 `git push`하면 권한 오류가 난다.
- 지금은 브라우저에서 dalseongsoft로 전환한 뒤 `폴더경로` 업로드 화면
  (`https://github.com/dalseongsoft/dalseongsoft.github.io/upload/main/<폴더>`)으로 올린다.
  같은 이름 파일을 올리면 덮어쓴다. 올린 뒤 로컬은 `git fetch; git reset --hard origin/main`으로 맞춘다.
- 404.html은 루트 배포 기준 절대경로(`/assets/...`)를 씀다.
- GitHub에 올리는 것은 사용자 허락을 받은 뒤에만 한다.

## 남은 일
- [ ] AdMob 계정 생성 후 `app-ads.txt` 추가 (`google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0`)
- [ ] 첫 앱 출시 시 홈 "앱" 영역과 방침 9번 "앱별 처리 내용" 채우기
- [ ] Play Console 개발자 웹사이트 칸에 이 사이트 주소 입력

## 사업자 정보 (D-U-N-S 신청값과 글자 하나까지 동일하게 유지)

- DALSEONG SOFT / 달성소프트, 사업자등록번호 558-30-01897, 대표 KWAK JONG(곽종)
- 31-24 Jinyeoul-gil 256beon-gil, Seoseok-myeon, Hongcheon-gun, Gangwon-do, 25165, Republic of Korea
