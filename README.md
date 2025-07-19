# Computer Vision Researcher Portfolio

Computer Vision 연구자를 위한 현대적이고 감각적인 포트폴리오 웹사이트입니다. Hugo 정적 사이트 생성기를 사용하여 구축되었습니다.

## 🚀 특징

- **현대적인 디자인**: 깔끔하고 전문적인 UI/UX
- **반응형 레이아웃**: 모든 디바이스에서 최적화된 경험
- **빠른 로딩**: 정적 사이트로 빠른 성능
- **SEO 최적화**: 검색 엔진 최적화
- **마크다운 지원**: 쉬운 콘텐츠 관리

## 🛠 기술 스택

- **정적 사이트 생성기**: Hugo
- **스타일링**: CSS3, Flexbox, Grid
- **애니메이션**: CSS Animations, JavaScript
- **폰트**: Inter (Google Fonts)
- **아이콘**: Font Awesome

## 📁 프로젝트 구조

```
medicalissue.github.io/
├── content/           # 마크다운 콘텐츠
│   └── research/      # 연구 프로젝트
├── themes/           # Hugo 테마
│   └── cv-portfolio/ # 커스텀 테마
├── static/           # 정적 파일
├── layouts/          # 레이아웃 템플릿
└── hugo.toml         # Hugo 설정
```

## 🚀 시작하기

### 1. Hugo 설치

```bash
# macOS
brew install hugo

# Windows
choco install hugo

# Linux
sudo apt-get install hugo
```

### 2. 로컬 개발 서버 실행

```bash
hugo server --buildDrafts
```

웹사이트는 `http://localhost:1313`에서 확인할 수 있습니다.

### 3. 빌드

```bash
hugo
```

빌드된 파일은 `public/` 디렉토리에 생성됩니다.

## 📝 콘텐츠 관리

### 새로운 연구 프로젝트 추가

```bash
hugo new content research/프로젝트명.md
```

### 마크다운 프론트매터 예시

```yaml
---
title: "프로젝트 제목"
date: 2024-01-15
draft: false
tags: ["Python", "PyTorch", "Computer Vision"]
summary: "프로젝트 요약"
---
```

## 🎨 커스터마이징

### 색상 변경

`themes/cv-portfolio/assets/css/main.css`에서 색상 변수를 수정하세요:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #ffd700;
    --text-color: #333;
}
```

### 폰트 변경

Google Fonts에서 원하는 폰트를 선택하고 `layouts/_default/baseof.html`에서 링크를 수정하세요.

## 📱 반응형 디자인

웹사이트는 다음 브레이크포인트에서 최적화됩니다:

- **데스크톱**: 1200px 이상
- **태블릿**: 768px - 1199px
- **모바일**: 767px 이하

## 🚀 배포

### GitHub Pages

1. GitHub 저장소 생성
2. `public/` 디렉토리를 `gh-pages` 브랜치로 푸시
3. GitHub Pages 설정에서 소스 브랜치를 `gh-pages`로 설정

### Netlify

1. Netlify 계정 생성
2. GitHub 저장소 연결
3. 빌드 명령어: `hugo`
4. 배포 디렉토리: `public`

## 📄 라이선스

MIT License

## 🤝 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

- **이메일**: researcher@university.edu
- **GitHub**: [yourusername](https://github.com/yourusername)
- **LinkedIn**: [yourprofile](https://linkedin.com/in/yourprofile)

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요! 