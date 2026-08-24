# GitHub Pages blog structure

이 저장소는 여러 글을 함께 운영하기 위한 간단한 정적 블로그 구조입니다.

```text
.
├── index.html
├── assets/
│   └── style.css
└── posts/
    └── riemann-zeta-symmetry.html
```

- `index.html`: 가벼운 글 목록/홈
- `posts/`: 실제 글 파일
- `assets/style.css`: 모든 글에서 공통으로 사용하는 스타일

새 글을 추가할 때는 `posts/새글.html`을 만들고 `index.html`에 카드 링크 하나만 추가하면 됩니다.

GitHub Pages에서는 저장소의 **Settings → Pages → Deploy from a branch → main / root**를 선택하면 됩니다.
