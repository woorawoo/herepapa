# 여기아빠 · 우상열 — Personal Brand Hub

`@herepapa`의 대표 링크(Link-in-bio) 허브 페이지입니다.

- 블로그: https://blog.naver.com/here_papa
- 포트폴리오: https://trail-portfolio-1111-698a.vercel.app/
- 피클(Pickle) AI 비서 초대: https://pickle.com/i/HGXCJJPV
- 협업·자문 문의: woorawoo@naver.com

## 구성

- 단일 정적 HTML 파일(`index.html`) — 빌드 과정 없음
- Pretendard 웹폰트(CDN), 반응형 1컬럼/카드형 레이아웃
- 이메일 복사 토스트, 스크롤 등장 효과 (바닐라 JS)

## 라이브

- https://woorawoo.github.io/herepapa/ (HTTP 200 확인)

## 운영 메모

GitHub Pages는 이 저장소의 **`gh-pages` 브랜치 루트**에서 배포됩니다.
내용을 고칠 때는 `main`을 수정한 뒤 `gh-pages`에도 반영해야 사이트에 게시됩니다.

    git checkout main && git commit -am "수정 내용" && git push origin main
    git checkout gh-pages && git merge main && git push origin gh-pages
