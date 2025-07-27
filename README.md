# StockPredictionUsingdifferentmodels
# 📈 TSLA Stock Price Prediction Under Constraints: A Comparative Study of Forecasting Models

This project investigates how different time series forecasting models perform on **Tesla (TSLA) stock price data** when constrained by:

- 🧠 **Low training data** (Jan 2024 – Jan 2025)
- 🖥️ **Limited compute resources** (Google Colab)
- ⚡ **Minimal tuning**

The models are tested on their ability to **predict Feb–Mar 2025 stock prices** using real-world historical data.

---

## 🚀 Models Compared

| Model | Type | Notes |
|-------|------|-------|
| **ARIMA** | Statistical | Simple, interpretable; strong baseline |
| **Reservoir Computing (RC)** | Dynamical | Echo State Network variant; fast to train |
| **MLP + Fourier Features** | Hybrid | Time-enhanced neural net |
| **XGBoost Regressor** | Tree-based ML | Feature-engineered from time series |
| **LSTM** | Deep Learning | Recurrent neural net for sequence learning |

---

## 🔍 Dataset

- Source: Yahoo Finance (via `yfinance`)
- Ticker: `TSLA`
- Timeframe: **Jan 2024 to Mar 2025**
- Features: `Date`, `Close`

---

## 📊 Evaluation Metrics

- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Square Error)
- **MAPE** (Mean Absolute Percentage Error)
- **Prediction Plots** vs. Actual Data

Example:


