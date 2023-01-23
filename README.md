# JOBATHON_JAN23_rank_10
Hello all this is a public repo that has the approach for JOBATHON_JAN23 with Private leaderboard rank of 10
**Approach:**
- **Data Preprocessing and Feature Engineering:**
  - Add more features using feature concatenation on all Categorical data.
  - Feature Interactions between claim amount and vintage like divide and multiply were used.
  - Binning the numerical columns like Claim amount.
  - Using Mean encoding of Target by leaking it to the test data.
  - Label Encoding
- **Feature Selection:**
  - Sequential Feature selection using Xgboost
- **Tuning:**
  - Tuning both Xgboost and Catboost models with best features.
- **Blending:**
  - Final Blending of XGBOOST and CATBOOST with 0.8, 0.2 as co-efficients.
