# datamap-data-seoul

데이터 압축지도(https://340patrolman.github.io/datamap/)가 읽는 **서울 지역 자료**다. 사람이 볼 페이지가 아니다(검색 차단).
- 구성: `manifest.json`(시군구 → 층 · 바이트 · 상자) · `r/<시군구 5자리>/<층>.json`
- 출처·라이선스: 파일마다 `source` 칸에 적었다(공공데이터포털·서울 열린데이터광장·경기데이터드림·통계청 SGIS·국토교통부·도로교통공단 TAAS·OpenStreetMap(ODbL) 등). 공공누리 표시 조건을 따른다.
- 기록을 쌓지 않는다: 자료를 다시 구우면 커밋 하나로 갈아 끼운다(지난 판은 지도 저장소 `tools/` 로 다시 구울 수 있다).
