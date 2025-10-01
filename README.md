# 📈 Basic Time Series Forecasting
*This repository is prepared for the **INT3209E_1 Data Mining course seminar** 🎓*
<br>

![Python](https://img.shields.io/badge/Python-3.11-blue)

🐍 **Libraries used:**  
- `pandas` – data manipulation  
- `numpy` – numerical computations  
- `matplotlib` / `seaborn` – visualization  
- `statsmodels` – AR, MA, ARMA, ARIMA modeling  
- `scikit-learn` – performance metrics, preprocessing, PCA
- `pmdarima` – auto ARIMA modeling

---

## 📊 Overview

This repository contains **basic time series forecasting projects** using **PCA dimensionality reduction combined with ARIMA models** in Python.  
The goal is to learn how to **analyze, model, and forecast time series data** in practice, with clean, reproducible code.

We cover both types of time series data:

- **Univariate Time Series**: Only one variable is tracked over time.  
  *Example:* Monthly AirPassengers dataset.  

- **Multivariate Time Series**: Multiple variables are tracked over time, which may influence each other.  
  *Example:* Daily Climate dataset.  

---

## 🛠️ Features

- Load and preprocess **time series datasets** (AirPassengers, Bitcoin, etc.)  
- Visualize **trends, seasonality, and residuals**
- **StandardScaler** for data normalization
- **PCA (Principal Component Analysis)** for dimensionality reduction
- **Latent variable extraction** and analysis
- Build models:
  - **AR (Autoregressive)**  
  - **MA (Moving Average)**  
  - **ARMA (Autoregressive Moving Average)**  
  - **ARIMA (Autoregressive Integrated Moving Average)**  
- Evaluate model performance:
  - **MSE (Mean Squared Error)**  
  - **MAE (Mean Absolute Error)**  
  - **R² Score**  
- Plot forecasts and **confidence intervals**  

---

