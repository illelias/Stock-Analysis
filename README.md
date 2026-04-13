# 📈 AAPL Stock Analysis & Forecasting  

---

## 📌 Overview  

This project analyzes and forecasts stock price movements for Apple Inc. (AAPL) using a combination of:

- 📊 Technical Analysis (SMA Strategy)  
- 📉 Time Series Forecasting (ARIMA/SARIMA)  

The goal is to evaluate market trends and compare predictive modeling approaches for financial data.

---

## 📂 Dataset  

- Stock: AAPL  
- Time Period: May → October 2025  
- Feature: Adjusted Closing Price  

The dataset captures:
- Short-term volatility  
- Mid-period dip (July–August)  
- Strong upward trend (September–October)  

---

## 🛠️ Tech Stack  

| Category | Tools |
|--------|------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Modeling | Statsmodels (ARIMA, SARIMA) |

---

## 🔍 Project Workflow  

### 📊 1. Data Preparation  
- Cleaned and structured time series data  
- Focused on adjusted closing prices  

---

### 📈 2. Double SMA Trading Strategy  

- Short-Term SMA: 20-day  
- Long-Term SMA: 50-day  

Signals:
- Buy → 20-day crosses above 50-day  
- Sell → 20-day crosses below 50-day  

Insight:  
- Identified a strong buy signal in August  
- No sell signal → sustained upward trend  

---

### 📉 3. Time Series Forecasting  

ARIMA (5,1,2):
- Conservative predictions  
- Low variance  
- Captures general trend  

---

### ⚖️ 4. Model Comparison  

| Model | Behavior | Insight |
|------|--------|--------|
| ARIMA (3,1,1) | Flat | Underfitting |
| ARIMA (7,1,3) | Slight trend | Moderate fit |
| SARIMA (2,1,1)(1,1,1,5) | Strong trend | Best performance |

---

## 📈 Results  

- Best Model: SARIMA  
- Trend: Bullish momentum  

Combining technical indicators and statistical models provides stronger insights.

---

## 🚀 How to Run  

```bash
git clone https://github.com/yourusername/aapl-forecasting.git
pip install pandas numpy matplotlib statsmodels
jupyter notebook CUS_690.ipynb
```

---

## 📎 Project Structure  

```
├── CUS_690.ipynb
├── images/
├── README.md
```

---

## 🎯 Key Takeaways  

- SMA crossover identifies trend changes  
- ARIMA struggles with momentum markets  
- SARIMA captures seasonality better  
- Hybrid approaches improve forecasting  

---

## 🔮 Future Improvements  

- LSTM / GRU models  
- Hyperparameter tuning  
- Backtesting strategies  
- Dashboard deployment  

---

## 👤 Author  

Elias Illescas  
M.S. Data Science – St. John’s University  
U.S. Navy Veteran  

---
