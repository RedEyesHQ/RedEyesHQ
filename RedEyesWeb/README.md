# RedEyes Game Studio Website

RedEyes 게임 개발 회사의 공식 웹사이트입니다.

## 🎮 프로젝트 소개

RedEyes는 혁신적이고 몰입감 넘치는 게임 경험을 제공하는 게임 개발 스튜디오입니다. 이 웹사이트는 회사의 비전, 게임 포트폴리오, 팀 소개 및 연락처 정보를 제공합니다.

## 🚀 기술 스택

- **HTML5**: 웹 페이지 구조
- **CSS3**: 모던한 스타일링 및 애니메이션
- **JavaScript (Vanilla)**: 인터랙티브 기능 구현
- **Google Fonts**: Orbitron, Noto Sans KR 폰트

## ✨ 주요 기능

### 1. 반응형 디자인
- 데스크톱, 태블릿, 모바일 모든 기기에서 최적화된 레이아웃
- 모바일 햄버거 메뉴 네비게이션

### 2. 인터랙티브 UI/UX
- 부드러운 스크롤 애니메이션
- Glitch 효과가 적용된 타이틀
- 호버 시 나타나는 게임 오버레이
- 패럴랙스 스크롤링 효과

### 3. 섹션 구성
- **Hero**: 눈에 띄는 메인 비주얼과 CTA 버튼
- **About**: 회사 소개 및 통계
- **Games**: 게임 포트폴리오 그리드
- **Team**: 팀 멤버 소개
- **Contact**: 문의 폼 및 연락처 정보

### 4. 애니메이션 효과
- Intersection Observer를 활용한 스크롤 애니메이션
- 통계 카운터 애니메이션
- 플로팅 애니메이션
- 버튼 호버 효과

## 📁 파일 구조

```
RedEyesWeb/
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 기능
├── README.md           # 프로젝트 문서
└── images/             # 이미지 폴더
    └── games/          # 게임 이미지
        ├── shadow-realm.svg
        ├── cyber-nexus.svg
        └── mystic-quest.svg
```

## 🎨 디자인 특징

### 컬러 팔레트
- **Primary Color**: `#ff0033` (레드 - 브랜드 컬러)
- **Secondary Color**: `#00ffff` (시안 - 액센트)
- **Background**: `#0a0a0a` / `#000000` (다크 테마)
- **Text**: `#ffffff` / `#a0a0a0` (라이트/그레이)

### 타이포그래피
- **헤딩**: Orbitron (게이밍 스타일 폰트)
- **본문**: Noto Sans KR (가독성 좋은 한글 폰트)

## 🔧 사용 방법

### 로컬 실행

1. 프로젝트 폴더를 다운로드하거나 클론합니다
2. `index.html` 파일을 웹 브라우저로 열기
3. 또는 로컬 서버를 실행:

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 패키지 필요)
npx http-server
```

4. 브라우저에서 `http://localhost:8000` 접속

### 커스터마이징

#### 색상 변경
`styles.css` 파일의 CSS 변수를 수정:

```css
:root {
    --primary-color: #ff0033;
    --secondary-color: #00ffff;
    /* ... */
}
```

#### 콘텐츠 수정
`index.html` 파일에서 텍스트, 이미지, 링크를 원하는 내용으로 변경

#### 기능 추가
`script.js` 파일에 새로운 JavaScript 기능 추가

#### 게임 이미지 교체
1. `images/games/` 폴더에 새로운 게임 이미지를 추가 (권장 크기: 800x600px)
2. 이미지 형식: JPG, PNG, SVG 모두 지원
3. `index.html`에서 이미지 경로 수정:
```html
<img src="images/games/your-game-image.jpg" alt="게임 이름">
```

## 📱 반응형 브레이크포인트

- **Desktop**: > 968px
- **Tablet**: 481px - 968px
- **Mobile**: ≤ 480px

## 🌟 주요 개선 가능 사항

1. **이미지 추가**: 실제 게임 스크린샷 및 팀 사진
2. **백엔드 연동**: 문의 폼을 실제 이메일 또는 데이터베이스와 연결
3. **다국어 지원**: i18n 라이브러리를 사용한 영어/한국어 전환
4. **CMS 통합**: 게임 정보를 동적으로 관리할 수 있는 CMS 연동
5. **성능 최적화**: 이미지 지연 로딩, 코드 번들링
6. **SEO 최적화**: 메타 태그, 구조화된 데이터 추가

## 📝 라이선스

© 2024 RedEyes Game Studio. All rights reserved.

## 🤝 기여

프로젝트 개선을 위한 제안이나 버그 리포트는 언제나 환영합니다!

---

**Made with ❤️ by RedEyes Team**

