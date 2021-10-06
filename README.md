## NextJS 적용 내용

- [x] 페이지 레이아웃 (Intro, Page layout)
- [x] Dynamic Routes, next/link
- [x] 서버사이드 렌더링 (Server-side Rendering/SSR/Dynamic Rendering)
- [x] 에러 페이지, 환경 변수 (Custom Error Page, Environment Variables)
- [x] 정적 생성(Sktatic Generation) - getStaticProps, getStaticPaths
- [x] isFallback

## 시연 영상

![시연 영상](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/0f8313c1-515d-4d31-b9bc-9868b9e5a690/nextjs.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20211006%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20211006T145703Z&X-Amz-Expires=86400&X-Amz-Signature=ae3b89b25c3ba76a8a37ccd1bb3b569bcee21e1734dfbd2e474a27a5452837e3&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22nextjs.gif%22)

## 설치 및 시작 방법

```bash
// [development]
//.env.development 파일에 apiUrl 작성
npm run dev

// [production]
//.env.production 파일에 apiUrl 작성
npm run build && npm run start
```
