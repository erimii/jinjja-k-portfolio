# K+DUCK 개발 포트폴리오

K-드라마 장면을 보며 숨은 문화 맥락, 표현, 장면 정보를 이해할 수 있도록 만든 K+DUCK 프로젝트 포트폴리오입니다.
웹 서비스, 관리자 콘솔, 학습형 MVP2 사례를 각각 확인할 수 있습니다.

## 바로 보기

- K+DUCK Home 포트폴리오: https://erimii.github.io/jinjja-k-portfolio/
- K+DUCK Home 기존 PDF: [JinJJa-K-Portfolio.pdf](./JinJJa-K-Portfolio.pdf)
- K+DUCK Home 별도 케이스 스터디: https://erimii.github.io/jinjja-k-portfolio/kduck-home/
- K+DUCK Home 별도 케이스 스터디 PDF: [KDUCK-Home-Portfolio.pdf](./KDUCK-Home-Portfolio.pdf)
- MVP2 케이스 스터디: https://erimii.github.io/jinjja-k-portfolio/mvp2/
- MVP2 PDF: [mvp2/KDUCK_MVP2_Final_Portfolio.pdf](./mvp2/KDUCK_MVP2_Final_Portfolio.pdf)

## 포함된 내용

- 제출용 HTML 포트폴리오
- PDF 포트폴리오
- 실제 앱 화면을 기반으로 캡처한 스크린샷
- 이력서에 활용할 수 있는 프로젝트 설명과 핵심 기여 내용

## 프로젝트에서 보여주는 내용

- React/TypeScript 기반 K-콘텐츠 학습 흐름 구현
- 콘텐츠 manifest, 자막 타이밍, 로마자 표기, 연기 대사 메타데이터 설계
- 브라우저 미디어 API인 getUserMedia와 MediaRecorder를 활용한 녹화 흐름 구현
- PWA 캐시, R2 미디어 경로, Cloudflare Pages/Functions 환경 검증
- local/dev/Android WebView 실행 환경 차이 분석 및 디버깅
- K+DUCK Home 공개 앱, 관리자 콘솔, 분석 파이프라인, 푸시 자동화, 보안 경계 설계

## 파일 구성

```text
.
├── README.md
├── index.html
├── JinJJa-K-Portfolio.pdf
├── KDUCK-Home-Portfolio.html
├── KDUCK-Home-Portfolio.pdf
├── images/
├── kduck-home/
│   └── index.html
└── mvp2/
    ├── index.html
    ├── KDUCK_MVP2_Final_Portfolio.pdf
    └── images/
```

## 기술 스택

React, TypeScript, Vite, Cloudflare Pages Functions, D1, R2, Workers, HLS, FCM Push, Cloudflare Access.
