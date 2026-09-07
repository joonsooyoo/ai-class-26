# 인공지능의이해 2026

사이버보안 강의 사이트와 동일한 디자인을 사용하는 정적 강의 홈페이지입니다.

- `index.html`: 강의 홈 및 공지
- `syllabus.html`: 강의 소개와 평가 비율 (중간 30%, 기말 40%, 출석 10%, 과제물 20%)
- `lectures.html`: 1주차 Orientation 자료, 2주차 YouTube 강의 2개 및 자료
- `exams.html`: 시험 안내
- `style.css`: 공통 스타일 및 모바일 대응

## 로컬 미리보기

이 폴더에서 다음 명령을 실행한 뒤 http://localhost:8000 에 접속합니다.

```sh
python3 -m http.server 8000
```

## 강의 추가

`lectures.html`의 `.lecture-row`를 복사하여 주차, 강의명, YouTube 링크를 수정합니다.

## 게시

빌드 없이 정적 파일을 웹 서버 또는 GitHub Pages에 게시할 수 있습니다.
GitHub Pages는 GitHub Actions로 배포합니다. `main` 브랜치에 push하면 `.github/workflows/pages.yml`이 사이트를 자동 게시합니다.

운영 주소: https://joonsooyoo.github.io/ai-class-26/

강의자료는 `asset/note/ai_week01.pdf`, `asset/note/ai_week02.pdf`에 있습니다.
