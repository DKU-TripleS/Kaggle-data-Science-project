# Kaggle-data-Science-Contest

## ⚡ DKU Data Science Competition 2025

스마트 팩토리 전력 예측 AI 챌린지
공장의 전력 소비 시계열 데이터를 기반으로 미래 전력 사용량을 예측하는 AI 모델을 개발하는 대회입니다.

목표: 시간별/일별/주별 전력 사용량 및 5월 전체 전기요금·탄소배출량 예측

데이터: 센서 기반 시계열 (전압, 전류, activePower, accumActiveEnergy 등)

평가 지표: MAE, RMSE, SMAPE, Bell-curve 점수

모델 예시: ARIMA, XGBoost, LSTM, Transformer

📅 2025.04.16 ~ 2025.05.29

🔗 https://www.kaggle.com/competitions/dku-data-science


## 🏆 성과 (Achievements)

리더보드: Public Leader Board 7위 / Private Leader Board 1위 달성

모델 성능: RMSE = 8.38, MAE = 0.7395 ,SMAPE = 0.0247%

접근 방식: EDA(시계열 특성 파악) → 계절성 분해 후 이상치 보간 → 노이즈 제거 → 성능 향상을 위한 파생 변수 추가 → XGBoost 학습 및 예측 → scaled factor(4월 실제값 / 4월 예측값) 반영 → 5월 전력사용량, 전기요금, 탄소배출량 예측

### 📚 배운 점 
- 시계열 데이터는 단순히 모델에 넣기보다 계절성 분해와 이상치·노이즈 처리가 중요하다는 점을 알게 되었고, 파생 변수 생성과 스케일링 보정이 성능 향상에 효과적임을 경험했습니다. 또한 딥러닝보다 XGBoost와 후처리 조합이 더 안정적인 결과를 제공한다는 사실을 확인했으며, 단순 예측을 넘어 전기요금과 탄소배출량까지 확장함으로써 ESG 관점의 실무적 감각도 배울 수 있었습니다.

