# 🌍 Weather Trend Forecasting – PM Accelerator Tech Assessment

## PM Accelerator Mission
"I’m on a mission to help launch 1,000+ AI products and empower professionals like you to become the next generation of AI product leaders — impacting millions of lives through real-world innovation."

---

## 📌 Project Objective
This project analyzes the Global Weather Repository dataset to:
- Perform data cleaning and exploratory data analysis
- Forecast future temperature trends
- Compare multiple forecasting models
- Build an ensemble model
- Perform advanced climate and environmental analyses
- Identify spatial and anomaly patterns

---

## 📊 Dataset
Source: Kaggle – Global Weather Repository  
Contains daily weather data for cities worldwide with 40+ features.

---

## 🔎 Methodology

### 1. Data Cleaning
- Missing value imputation (forward fill + seasonal median)
- Outlier detection using IQR & Isolation Forest
- Time-series formatting using `last_updated`
- Aggregation per city per day

### 2. Exploratory Data Analysis
- Temperature & precipitation trends
- Correlation heatmap
- Seasonal pattern analysis
- Spatial temperature distribution

### 3. Forecasting Models
Models built and compared:
- Naive Baseline
- SARIMAX
- Prophet
- XGBoost Regressor
- Ensemble (Weighted average)

Metrics used:
- MAE
- RMSE
- sMAPE

### 4. Advanced Analyses
- Anomaly detection (STL + Isolation Forest)
- Climate long-term trend analysis
- Air quality impact correlation
- Feature importance (SHAP)
- Spatial heatmaps

---

## 🚀 How to Run

1. Install dependencies:
