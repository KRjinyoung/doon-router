# doon.land

DOON 공정 티켓팅의 지역 PoP 라우터.

브라우저 위치(Geolocation API)로 가장 가까운 PoP를 계산해 연결한다.
위치는 브라우저 안에서만 쓰이고 서버로 전송되지 않는다.

- PoP 목록과 좌표: [`pops.json`](pops.json). 새 지역은 항목 하나를 추가하면 된다.
- `?loc=busan`: 해당 지역에서 접속한 것으로 계산 (시연용, 화면에 시뮬레이션 표시)
- `?pop=pop-daejeon`: 지정한 PoP로 바로 연결

위치 권한은 HTTPS에서만 동작하므로 GitHub Pages로 배포한다.

본 서비스 저장소: DOON (K-디지털 챌린지: 넷 챌린지 캠프 시즌13 · Team Doon)
