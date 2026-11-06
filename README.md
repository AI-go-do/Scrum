# Scrum
## Discussion 자동 게시

`posts/` 아래에 `.md` 파일을 `main`이나 `posts` 브랜치에 push하면 [Post Discussion](.github/workflows/post-discussion.yml) Actions가 Discussion 글을 만들어요.

```
제목: [스크럼] 1주차 6일차 11/6(금)
카테고리: scrum
---
## 공통
...
```

- `카테고리`는 카테고리 이름이나 slug(`scrum`, `sprint`). 없으면 `scrum`
- 같은 제목 글이 이미 있으면 다시 만들지 않아요
- Actions 탭에서 파일 경로를 넣고 직접 실행할 수도 있어요
