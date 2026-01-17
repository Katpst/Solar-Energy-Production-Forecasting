Solar Energy Production Forecasting

This project builds an end-to-end machine learning pipeline to forecast hourly solar energy production for 15 power plants, using historical weather data and time-series feature engineering.
The final model selection is based on RMSE and R², with explicit comparison against a provided benchmark forecast.

---

## Objectives

* Build a leakage-safe time-series ML pipeline for panel data
* Engineer temporal, cyclical, lag, and rolling features
* Reduce multicollinearity in weather variables using PCA
* Compare multiple models:

  * Linear (Ridge, Lasso)
  * Distance-based (KNN)
  * Tree-based & Ensembles (Random Forest, Gradient Boosting, XGBoost, LightGBM)
* Interpret the final model using global and local explainability (XAI)
* Quantify performance vs benchmark

## Results

* Tree-based boosting models outperform linear and distance-based models
* PCA improves stability for linear/KNN models, but not for boosting
* Final model achieves a lower RMSE and higher R² than the benchmark
* Weather patterns + lagged production are the strongest drivers

(Exact numbers reported in the notebook)




