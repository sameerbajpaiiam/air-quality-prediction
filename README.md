# Predictive Environmental Modelling & Multivariate Air Quality Analysis

**High-Performance Multi-Output Regression Pipeline**

Architected a robust pipeline to forecast **Temperature (T)**, **Relative Humidity (RH)**, and **Absolute Humidity (AH)** from air-quality sensor data (AirQualityUCI dataset).

## Key Results
- **Best Model**: XGBoost Regressor  
  - Parameters: `n_estimators=300`, `learning_rate=0.05`, `max_depth=6`
- **Performance**: **R² = 0.91** | **RMSE = 4.10**
- Built and compared **Random Forest Regressor** (`n_estimators=200`, `max_depth=10`)
- Performed **feature importance ranking** on both models with side-by-side comparison plot

## Key Findings
- Top chemical precursors: **CO(GT)**, **NO₂(GT)**, and **NMHC(GT)**
- Engineered temporal features: Month, DayOfWeek, Hour

## Data Pipeline Highlights
- Non-standard semicolon delimiter + comma decimal handling
- Replaced sentinel value `-200` with NaN → mean imputation
- 13 input features (temporal + 10 sensors)

## Tech Stack
- Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn
- Models saved: `xgb_model.json` + `random_forest_model.joblib`

## Notebooks & Scripts
- [Untitled2.ipynb](https://github.com/sameerbajpaiiam/air-quality-prediction/blob/main/Untitled2.ipynb)
- [untitled2.py](https://github.com/sameerbajpaiiam/air-quality-prediction/blob/main/untitled2.py) (exported script)

**Repository**: [GitHub](https://github.com/sameerbajpaiiam/air-quality-prediction)
