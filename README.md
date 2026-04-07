Markdown# Predictive Environmental Modelling & Multivariate Air Quality Analysis

**High-Performance Regression Pipeline (XGBoost + Random Forest)**

Architected a robust multi-output regression pipeline to forecast critical environmental variables (**Temperature**, **Relative Humidity**, and **Absolute Humidity**) from air quality sensor data.

## Key Results
- **Best Model**: XGBoost Regressor  
- **Performance**: **R² = 0.91** | **RMSE = 4.10**
- Built and compared **Random Forest Regressor** alongside XGBoost
- Performed **feature importance ranking** on both models to identify the most influential variables

## Key Findings
- Identified **CO**, **NO₂**, and **NMHC** as the top chemical precursors most indicative of environmental shifts and diurnal patterns.
- Temporal features (Month, DayOfWeek, Hour) + sensor readings were engineered for maximum predictive power.

## Tech Stack
- Python, Pandas, Scikit-learn, XGBoost
- Custom data pipelines (non-standard `;` delimiter + mean imputation for missing values)

## Notebooks
- [Open in Colab](https://colab.research.google.com/github/sameerbajpaiiam/air-quality-prediction/blob/main/Untitled2.ipynb)

**Repository**: [GitHub](https://github.com/sameerbajpaiiam/air-quality-prediction)
