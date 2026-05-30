# 변경히스토리

## 2026-05-31

- 게시판/채팅 저장소를 브라우저 `localStorage`에서 Supabase `posts`/`messages` 테이블로 전환
- Supabase Realtime 구독 추가로 다른 기기에서 작성된 글/메시지가 자동 반영되도록 변경
- Supabase insert 성공 시 작성자 화면에 즉시 반영하고 Broadcast로 열린 탭/기기에 전파되도록 보강
- 채팅 화면을 모바일 메신저형 말풍선 UI와 하단 입력바 구조로 개선
- 정적 HTML 일정표를 React 기반 단일 페이지 앱으로 전환
- 새 탭 추가: `게시판`, `채팅`
- 게시판 글쓰기/목록 기능 추가: 작성자, 카테고리, 제목, 내용, 작성시간 저장
- 가족 채팅 입력/목록 기능 추가
- 게시판/채팅 데이터는 현재 브라우저 `localStorage`에 저장되도록 구현
- 추후 Supabase 실시간 DB로 전환할 수 있도록 데이터 필드 구조 정리
- 모바일 화면에 `일정`, `준비물`, `지도`, `메모` 탭 구조 추가
- `준비물 체크리스트` 섹션 추가: 서류/결제, 전자기기, 남자 3명, 여자 3명, 임산부 메모, 공용, 해변용품
- 지도 바로가기 허브 추가 및 Google Maps 버튼 유지
- 모바일 가독성 개선: sticky 탭, 카드형 준비물, 텍스트 overflow 방지, 부드러운 체크포인트 톤 적용
- 디자이너/퍼블 역할을 추가 운용하고, PL 검증 후 배포하는 훅 방식 적용
- 에이전트 역할명을 `PL`, `개발1`, `개발2`, `검증`, `배포`, `프로젝트설명`으로 정리
- `AGENT_ROLES.md`에 역할 및 보고 규칙 추가
- `hawaii-trip.md`에 하와이 일정표 v1 저장
- `hawaii-itinerary.html` 생성
- `index.html` 생성으로 GitHub Pages 엔트리 준비
- `README.md`, `.nojekyll` 생성
- GitHub 저장소 `https://github.com/Henry-NonstopK/hawaii-itinerary.git`에 `main`, `gh-pages` 브랜치 push 성공
- GitHub Pages URL `https://henry-nonstopk.github.io/hawaii-itinerary/` 빌드 및 접속 확인
- 기존 역할 정리를 새 역할명 체계로 변경
