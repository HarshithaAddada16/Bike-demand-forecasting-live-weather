# Bike-demand-forecasting-live-weather
End-to-end machine learning project forecasting hourly bike rental demand using time-series features, ensemble models, and real-time weather data integration.

## 🚲 Capital Bike Sharing Demand Forecasting (Live Weather Enabled)

An end-to-end machine learning forecasting project that predicts hourly bike rental demand using historical usage data, engineered time-series features, and real-time weather data integration.
The solution is designed to be production-ready, time-aware, and deployment focused.

## 🔧 Tech Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · LightGBM · CatBoost · Optuna · Matplotlib · Seaborn · Live Weather API

## 🔍 What This Project Does

Cleans and validates hourly Capital Bikeshare data

Performs structured EDA to understand temporal and weather effects

Engineers time-series features (lags, rolling stats, cyclical encoding)

Uses time-aware train/test split (last 50 days as unseen future data)

Trains and tunes multiple ML models using Optuna

Integrates live weather data to generate real-time demand forecasts

## ⚙️ Modeling Approach

Baseline models: Linear, Ridge, Lasso, Random Forest

Advanced models:

Histogram Gradient Boosting

XGBoost

LightGBM

CatBoost

Evaluation metrics: RMSE, MAE, SMAPE

Model performance compared using a leaderboard and prediction diagnostics

## 🌦️ Live Weather Integration

Fetches current weather data via API

Transforms live inputs using the same feature pipeline as training

Generates real-time bike demand predictions

Ensures consistency between historical and live forecasting

## 📊 Results & Insights

Bike demand follows strong hourly, weekly, and seasonal patterns

Weather variables (temperature, humidity, wind) significantly impact rentals

Tree-based ensemble models outperform linear models

Time-aware validation produces more realistic forecasting performance

Live weather integration enables dynamic, real-world predictions

## 🚀 Key Takeaways

Demonstrates full ML lifecycle: data → features → models → evaluation → live forecasting

Emphasizes production-oriented time-series modeling

Suitable for real-world deployment scenarios
