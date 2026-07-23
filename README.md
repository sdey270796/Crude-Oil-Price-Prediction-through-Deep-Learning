# 🛢️ Crude Oil Price Prediction using Deep Learning (LSTM)

> **An End-to-End Time Series Forecasting Project using Long Short-Term Memory (LSTM) Networks to Predict Brent and West Texas Intermediate (WTI) Crude Oil Prices**

This repository presents a comprehensive deep learning framework for forecasting **crude oil prices** using **Long Short-Term Memory (LSTM)** neural networks.

The project analyzes historical price movements of the world's two most influential crude oil benchmarks—**Brent Crude Oil** and **West Texas Intermediate (WTI)**—through exploratory time series analysis, trend decomposition, rolling statistics, deep learning modeling, and future price forecasting.

Designed as a complete **financial time series forecasting** project, the notebook demonstrates the full workflow from data acquisition to business interpretation.

---

# 🚀 Project Highlights

- 🛢️ Brent & WTI Crude Oil Price Forecasting
- 🧠 Deep Learning using LSTM Networks
- 📈 Time Series Forecasting
- 📊 Exploratory Time Series Analysis
- 📉 Trend & Seasonality Decomposition
- 📅 Rolling Average Analysis (100 & 200 Days)
- 📦 Data Scaling & Sequence Generation
- 📈 Future Price Prediction
- 📊 Model Performance Evaluation
- 💾 Trained Model Saving

---

# 📖 Project Overview

Crude oil prices are influenced by a wide range of economic, geopolitical, and market factors, making accurate forecasting both challenging and valuable.

This project develops separate **LSTM-based forecasting models** for:

- 🛢️ Brent Crude Oil
- 🛢️ West Texas Intermediate (WTI)

The models learn historical price patterns and generate forecasts for future crude oil prices, helping demonstrate how deep learning can capture complex temporal dependencies in financial data.

---

# 🎯 Objectives

The project aims to:

- Collect historical crude oil price data.
- Analyze long-term market trends.
- Study seasonality and temporal patterns.
- Develop LSTM-based forecasting models.
- Evaluate prediction performance.
- Forecast future crude oil prices.
- Compare Brent and WTI market behavior.

---

# 💼 Business Impact

Accurate crude oil price forecasting benefits:

- Energy Companies
- Petroleum Refineries
- Commodity Traders
- Financial Institutions
- Supply Chain Managers
- Government Agencies
- Investment Firms
- Risk Management Teams

by supporting better planning, budgeting, inventory management, and investment decisions.

---

# 🔄 Project Workflow

```
Historical Price Data
          │
          ▼
Data Collection
          │
          ▼
Data Cleaning
          │
          ▼
Time Series Analysis
          │
          ▼
Trend Decomposition
          │
          ▼
Rolling Statistics
          │
          ▼
Feature Scaling
          │
          ▼
Sequence Generation
          │
          ▼
LSTM Model Training
          │
          ▼
Prediction
          │
          ▼
Performance Evaluation
          │
          ▼
Future Price Forecasting
```

---

# 🧩 Project Pipeline

## 1. Data Collection

Historical market data is collected for:

- Brent Crude Oil
- West Texas Intermediate (WTI)

using financial market data sources.

---

## 2. Data Preprocessing

The preprocessing stage includes:

- Resetting index
- Removing unnecessary columns
- Missing value handling
- Time index preparation
- Data normalization

---

## 3. Exploratory Time Series Analysis

The project explores:

- Historical price movement
- Long-term trends
- Market volatility
- Price fluctuations

through informative visualizations.

---

## 4. Time Series Decomposition

The notebook decomposes the time series into:

- Trend
- Seasonality
- Residual Components

to better understand the underlying behavior of crude oil prices.

---

## 5. Rolling Average Analysis

Market trends are analyzed using:

- 100-Day Moving Average
- 200-Day Moving Average

to identify long-term market direction and smoothing effects.

---

## 6. Data Scaling

The project applies normalization before training to improve convergence and model stability.

---

## 7. LSTM Model Development

Separate LSTM models are developed for:

- Brent Crude Oil
- WTI Crude Oil

The models learn temporal dependencies from historical sequences to forecast future prices.

---

## 8. Model Evaluation

The forecasting models are evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Error Analysis
- Prediction Visualization
- Actual vs Predicted Comparison

---

## 9. Future Forecasting

The trained models generate forecasts for future crude oil prices, allowing comparison between predicted market movements for Brent and WTI benchmarks.

---

## 10. Comparative Analysis

The notebook concludes with a comparison of:

- Brent vs WTI Price Trends
- Normalized Means
- Forecast Performance
- Predicted Future Growth

to understand differences between the two global oil benchmarks.

---

# 🧠 Deep Learning Concepts Covered

This project demonstrates:

- Time Series Forecasting
- Long Short-Term Memory (LSTM)
- Sequential Neural Networks
- Sliding Window Sequences
- Data Normalization
- Regression Modeling
- Financial Forecasting
- Deep Learning for Time Series
- Model Evaluation

---

# 📊 Performance Metrics

The forecasting models are evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Prediction Error
- Visual Prediction Accuracy
- Actual vs Predicted Price Comparison

---

# 📈 Visualizations Included

The notebook generates numerous visualizations, including:

- Historical Price Trends
- Time Series Decomposition
- Trend Components
- Seasonal Components
- Residual Analysis
- 100-Day Rolling Average
- 200-Day Rolling Average
- Actual vs Predicted Prices
- Future Price Forecasts
- Brent vs WTI Comparative Charts

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- LSTM Networks
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Statsmodels
- Yahoo Finance API
- Google Colab

---

# 🎯 Applications

The techniques demonstrated in this project are applicable to:

- Commodity Price Forecasting
- Financial Time Series Analysis
- Investment Strategy
- Energy Market Analytics
- Risk Management
- Supply Chain Planning
- Economic Forecasting
- Algorithmic Trading

---

# 🎓 Learning Outcomes

After completing this project, readers will understand:

- How financial time series differ from traditional datasets.
- How LSTM networks capture sequential dependencies.
- How to preprocess data for time series forecasting.
- How moving averages reveal long-term market trends.
- How to evaluate forecasting models.
- How deep learning can be applied to commodity markets.

---

# ▶️ Getting Started

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook in **Google Colab** or **Jupyter Notebook**.
4. Run all notebook cells sequentially.
5. Train the LSTM models.
6. Evaluate the forecasts.
7. Explore future price predictions.

---

# 📌 Future Improvements

Potential enhancements include:

- GRU-Based Forecasting
- Transformer Models for Time Series
- Attention Mechanisms
- Multivariate Forecasting
- Incorporating Macroeconomic Indicators
- Sentiment Analysis from Financial News
- Hyperparameter Optimization
- Streamlit Dashboard
- Real-Time Price Forecasting
- Ensemble Forecasting Models

---

# 🤝 Contributions

Contributions are welcome! Feel free to fork this repository, improve the forecasting models, or submit pull requests.

---

# ⭐ Support the Project

If you found this repository useful for learning **Deep Learning**, **Time Series Forecasting**, **Financial Analytics**, or **Commodity Price Prediction**, consider giving it a **⭐ Star** to support future work.
