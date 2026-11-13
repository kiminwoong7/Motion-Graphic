# Motion Graphic

## Canon — 30″ Spot (`canon_ad/`)
16:9, 30초 모션그래픽 광고 (HTML/Canvas/Web Audio).

- 키네틱 타이포그래피, 조리개 오프닝, 뷰파인더 HUD, 셔터 플래시, 렌즈 플레어
- 배경음악: Web Audio로 실시간 합성한 에픽 오케스트라 스코어
- 내레이션: Web Speech API (슬로건 "Delighting You Always")
- 이미지: Canon 공식 사이트(global.canon) — 저작권은 Canon Inc.에 있음, 비상업적 포트폴리오/시안용

### 실행
```bash
python -m http.server 8765 --directory canon_ad
```
http://localhost:8765 → ▶ PLAY (R = 다시 재생, `?t=12` = 특정 시점 정지 프레임)

## WANDER — Enjoy Your Life (`travel/`)
38초 세계여행 청춘 모션그래픽 (16:9, HTML/Canvas/Web Audio).

- 한 명의 배낭여행자가 도시 → 순례길·히말라야·항해·서핑·열기구·오로라·뉴욕 루프탑 파티 → 마추픽추로 이어지는 여정
- 장소가 바뀔 때마다 비트에 맞춰 커졌다 작아지는 대형 타이틀, 한국어 여행 일기 자막
- 음악: Kevin MacLeod "Heroic Age" (incompetech.com, CC BY 4.0) — 130 BPM 박자에 컷·타이틀 펄스 동기화, 효과음(서브드롭·리버스 심벌·휘시·불꽃)은 Web Audio 합성
- 엔딩: ENJOY YOUR LIFE · 인생은 한 번, 지금 떠나라

### 사진 출처 (Wikimedia Commons / Wikipedia, 각 파일의 CC 라이선스를 따름)
Matterhorn from Domhütte · Shibuya Crossing, Aerial · New York Times Square (terabass) · Burj Khalifa and the Dubai skyline · Al Deir Petra · Ha Long Bay in 2019 · Camino Francés, Penas, Melide · Camino de Santiago (2671926522) · Mt. Everest from Gokyo Ri · Sailing (257088109) · Mavericks Surf Contest 2010b · Cappadocia balloon trip, Ortahisar Castle · Aurora borealis over Eielson AFB · City of lights (Unsplash) · Moraine Lake 17092005 · Canyon River Tree (165872763) · Machu Picchu, 2023 (012)
