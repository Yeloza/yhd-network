# YHD Mobile Test V8.8 — Connections

V8.7의 기능과 브랜딩을 유지하면서 추천 연결과 최근 동문 소식의 중복 노출을 정리한 버전입니다.

- Desktop (>1180px): 우측 사이드에 `오늘의 연결` + `YHD NOW`만 노출
- Mobile/Tablet (<=1180px): 홈 본문에 `만나보고 싶은 동문` + `YHD NOW`만 노출
- 동일 화면에서 추천/최근 소식이 중복되지 않음
- 추천 로직 `rankedAlumni()` 및 동문 소식 데이터는 그대로 사용
- 기존 `찾고 싶은 동문`, `나누고 싶은 재능`, `Story Doing` 기능 유지

테스트: `?demo=1&qa=1`
