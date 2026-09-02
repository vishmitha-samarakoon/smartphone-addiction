This repository contains my final solution for the Kaggle Playground Series S6E8 – Predicting Smartphone Addiction competition. The task was to predict the probability of smartphone addiction from behavioral and usage-related features.

My final submission achieved a Public AUC of 0.97054 and finished at Rank 618.

The solution uses a robust ensemble pipeline combining LightGBM, XGBoost, and CatBoost, together with 5-fold stratified cross-validation, fold-safe target encoding, feature engineering, and percentile-rank blending. The notebook is designed to be reproducible and can run directly in Kaggle with the competition dataset attached.

Final Result:
Public AUC: 0.97054
Rank: 618
Competition: Kaggle Playground Series S6E
