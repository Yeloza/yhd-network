# YHD Network

예학당 동문 네트워크 **YHD V8.8** 개발 저장소입니다.

## 바로 실행하기

[Open in StackBlitz](https://stackblitz.com/github/Yeloza/yhd-network)

StackBlitz에서 저장소를 열면 `npm start`가 자동 실행되고 브라우저 미리보기를 사용할 수 있습니다.

## 주요 파일

- `index.html` — YHD 전체 웹앱
- `manifest.webmanifest` — PWA 설정
- `sw.js` — 서비스워커
- `icon-180.png`, `icon-192.png`, `icon-512.png` — 앱 아이콘
- `_headers`, `_redirects` — Netlify용 설정

## 테스트 모드

주소 뒤에 아래 값을 붙이면 로그인 전에도 화면 테스트가 가능합니다.

```
?demo=1&qa=1
```

- `demo=1` — 데모 데이터/화면 테스트
- `qa=1` — 모바일 QA 보조 표시

## 개발 원칙

- 브랜드명은 **YHD**
- 기존 Supabase 연동 구조 유지
- 모바일/PWA 우선
- Story Doing · 동문 발견 · 연결 · 커뮤니티 흐름 유지
