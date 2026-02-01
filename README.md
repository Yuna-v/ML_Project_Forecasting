## ML Project: COVID-19 Forecasting
# Overview
This project develops time-series forecasting models to predict COVID-19 infection trends using data from the World Health Organization (WHO). The analysis includes data preprocessing, exploratory analysis, feature engineering, and implementation of multiple forecasting algorithms with performance evaluation.

# Dataset
Source: World Health Organization (WHO)
Type: Time-series data
Frequency: Daily COVID-19 case reports
Coverage: Global and regional infection data

Note: Large data files are not stored in this repository due to size constraints.

# Technologies

Python 3.8+
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn, statsmodels
Time-Series: Prophet, pmdarima

# Data Acquisition
Download the WHO COVID-19 dataset from https://covid19.who.int/data.

---

# Methodology
1. Data Preprocessing

- Handling missing values and outliers
- Data validation and quality checks
- Time-series alignment and resampling

2. Feature Engineering

- Lag features creation
- Rolling statistics (mean, std, min, max)
- Time-based features (day of week, month)

3. Modeling

- Machine Learning models: Random Forest, XGBoost (Regression models)
- Hyperameters optimization (Optuna)

4. Evaluation

- Feature importance 
- Train/validation/test split with temporal ordering
- Performance metrics: MAE, RMSE
- Cross-validation with time-series splits
- Residual analysis

# References

World Health Organization COVID-19 Dashboard: https://covid19.who.int/

# Authors
Fanny Xie & Guillaume Masson
