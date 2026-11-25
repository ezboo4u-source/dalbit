# 달빛강릉 홈페이지 (HOTEL 달빛강릉)

감성숙소 달빛강릉 홈페이지. 정적 사이트 — `index.html` 하나 + `assets/` 사진·영상.

- 히어로 슬로건: 강릉을 담다 강릉을 닮다 / 감성숙소 달빛강릉
- 객실 6타입 24개, 예약은 네이버 플레이스 링크로 연결
- 전화번호는 사이트에 없음 (카카오톡 QR로 문의)

## 배포 방법 (GitHub + Vercel)

1. GitHub에서 새 저장소 `ezboo4u-source/dalbit-gangneung` (Public) 생성
   — API로는 생성이 막혀 있어(403) 브라우저에서 직접 만들어야 함
2. 이 폴더 내용(`index.html`, `assets/`, `README.md`)을 저장소 루트에 업로드
   — 파일 160개, 총 약 57MB, 가장 큰 파일 약 8MB (웹 업로드 제한 25MB 이내)
3. Vercel에서 GitHub 저장소를 연결해 프로젝트 생성 후 프로덕션 배포
   — Vercel 팀(he-thinks1) 접근 권한이 끊겨 있으면 먼저 커넥터 재인증 필요

## 파일

- `index.html` — 홈페이지 전체 (사진·영상은 `assets/` 상대 경로 참조)
- `assets/` — 사진 152장 + 영상 7개 (원본 품질 그대로)
