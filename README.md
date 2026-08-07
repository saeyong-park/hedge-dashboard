# hedge-dashboard

AI Agent Hedge Fund 현황판 (페이퍼 트레이딩).
- `index.html` — 정적 페이지 (Vercel 호스팅)
- `data.json` — 5분마다 서버 systemd 타이머가 갱신 푸시 (렌더러: 메인 repo `scripts/render_dashboard.py`)
- 페이지는 raw.githubusercontent에서 data.json을 fetch — Vercel 재배포 없음
