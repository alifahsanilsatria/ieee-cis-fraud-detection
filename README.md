# ieee-cis-fraud-detection

This is for kaggle competition on this link:
https://www.kaggle.com/c/ieee-fraud-detection/overview

This competition using AUC-ROC as evaluation metrics (tentative):
1. submission raw features only (random forest) --> 0.819223
2. submission raw features only (xgboost) --> 0.835217
3. submission raw + engineered features + initial hyperparameter (xgboost) --> 0.847249
4. submission raw + engineered feature + hyperparameter tuning for max_depth, min_child_weight, and gamma (xgboost) --> 0.851137

Raw Features : Card, ProductCD, DeviceType, DeviceInfo, P_emaildomain, R_emaildomain, addr1, addr2, id_, TransactionAmt, dist, TransactionDT
Engineered Features : Cx, Dx, Mx, Vx

Important Notes contains what to be done with raw features
