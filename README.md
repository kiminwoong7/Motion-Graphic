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
