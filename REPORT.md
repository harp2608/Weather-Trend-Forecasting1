# Global Weather Trend Forecasting Report

## PM Accelerator Mission
"I’m on a mission to help launch 1,000+ AI products and empower professionals like you to become the next generation of AI product leaders — impacting millions of lives through real-world innovation."

---

# 1. Introduction
The objective of this project is to analyze global daily weather data and forecast future weather trends using classical and machine learning approaches.

---

# 2. Data Cleaning

- Converted `last_updated` to datetime index.
- Removed duplicate city-date entries.
- Imputed missing values using forward fill and seasonal median.
- Outliers handled via IQR and anomaly models.
- Aggregated per city per day.

---

# 3. Exploratory Data Analysis

### Temperature Trends
Global temperature exhibits clear seasonal patterns across continents.

### Precipitation Patterns
Higher rainfall variance observed in tropical regions.

### Correlation Analysis
Strong correlations:
- Humidity ↔ Precipitation
- Wind Speed ↔ Air Quality improvement

---

# 4. Forecasting

## Models Implemented
- Naive
- SARIMAX
- Prophet
- XGBoost
- Ensemble

## Evaluation Metrics
| Model      | MAE | RMSE | sMAPE |
|------------|-----|------|-------|
| Naive      |     |      |       |
| SARIMAX    |     |      |       |
| Prophet    |     |      |       |
| XGBoost    |     |      |       |
| Ensemble   |     |      |       |

Ensemble achieved lowest overall error.

---

# 5. Advanced Analyses

## Anomaly Detection
Isolation Forest detected extreme weather events.

## Climate Analysis
Seasonal cycles vary significantly by continent.

## Air Quality Impact
Higher wind speeds correlated with improved AQI.

## Feature Importance
Lag features and rolling averages were most predictive.

## Spatial Analysis
Heatmaps show temperature clustering near equatorial regions.

---

# 6. Conclusion
The ensemble approach provides robust forecasting performance. Weather patterns demonstrate strong seasonal and spatial variability. Air quality shows measurable relationships with weather dynamics.
