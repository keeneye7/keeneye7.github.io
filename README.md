# keeneyes

> Observations on engineering in the age of AI

## 배포 방법 — GitHub Pages

### 1. 레포지토리 생성

```bash
# 이미 keeneye7 계정이 있으므로
cd keeneye7.github.io
git init
git add .
git commit -m "feat: launch keeneyes blog with issue 01"
git branch -M main
git remote add origin https://github.com/keeneye7/keeneye7.github.io.git
git push -u origin main
```

### 2. GitHub Pages 활성화

1. https://github.com/keeneye7/keeneye7.github.io → Settings → Pages
2. Source: Deploy from a branch
3. Branch: main / root
4. Save

### 3. 접속

몇 분 후 `https://keeneye7.github.io` 에서 확인 가능.

## 구조

```
keeneye7.github.io/
├── index.html                      # 블로그 홈
├── posts/
│   └── 01-token-efficiency.html    # 첫 번째 글
└── README.md
```

## 글 추가 방법

`posts/` 폴더에 `02-xxx.html` 생성 후
`index.html`의 `<!-- POSTS -->` 섹션에 카드 추가.

## 프라이버시

- 실명 없음
- 회사명 없음
- 위치 없음
- GitHub 프로필만 연결
