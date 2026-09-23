# AA Model Telemetry

Artificial Analysis 벤치마크 데이터로 만든 비공식 시각화 뷰어.

- `index.html` - 모델별 원시 지표 뷰어(엔지니어링 점수, 작업당 토큰, 출력 속도, 토큰 가격, 작업당 비용/시간) + 3축 산점도
- `aa_compare.html` - 모델 여러 개를 골라 나란히 비교(레이더, 지표별 막대, 스펙 표, 파레토 판정)
- `aa_insights.html` - 고수준 분석(가격-성능 사다리, 시장 지형도, 효율 랭킹, 추론 분해, 제작사 지도, 상관 행렬)
- `aa_models_data.csv` - 정제된 원시 데이터(673개 모델)

데이터 출처: artificialanalysis.ai Models 페이지(2026-09-23 수집).
GLM-5.3 (max) 속도/시간은 사용자 실측값(220 tok/s)으로 보정.
