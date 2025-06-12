# 🛍️ Store Sales & Stock Forecasting Project

## 📌 Project Overview

This project is based on the [Store Sales Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) competition from Kaggle. The goal is to forecast future store sales using multivariate and univariate time series models.

The project is extended further to apply **time series forecasting on stock market data** using **Facebook Prophet**, helping to strengthen forecasting skills on real-world datasets.

---

## 🔍 Objectives

- Understand and implement time series forecasting techniques.
- Clean, preprocess, and analyze time-based data.
- Apply lag features and scaling techniques to build multivariate models.
- Train ensemble models (Random Forest, Bagging, Voting Regressors).
- Use **Prophet** for univariate time series forecasting on stock data.

---

## 🧠 Techniques Used

### Multivariate Time Series (Store Sales)
- Lag Features (`lag_1`, `lag_7`)
- Train-Test Split
- Standard Scaling
- Random Forest & Decision Tree Regressor
- Bagging & Voting Regressor
- RMSE evaluation

### Univariate Time Series (Stock Forecasting)
- Stock data via `yfinance`
- Data reshaping for Prophet (`ds`, `y`)
- Prophet Forecasting (30-day)
- Forecast Plotting

---

## 🧪 Results

- Achieved good test RMSE using RandomForest + Bagging Regressor.
- Generated future 30-day forecasts for Apple stock (AAPL) using Prophet.

---

