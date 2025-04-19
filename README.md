# Stock-Market-Prediction-App
## 📑 Table of Contents

1. [Project Overview](#project-overview)  
2. [Data Collection](#data-collection)  
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
   - Close Price vs Year  
   - Candlestick Chart (Plotly)  
   - Moving Averages (Plotly)  
4. [Time Series Forecasting Models](#time-series-forecasting-models)  
   - ARIMA & SARIMAX (Not Used in Deployment)  
   - Deep Learning & Advanced Forecasting Models  
     - LSTM Model  
     - Facebook Prophet  
5. [Deployment](#deployment)  
   - Streamlit App Features  
   - Model Selection & Forecasting Options  
6. [Model Files Used for Deployment](#model-files-used-for-deployment)  
   - LSTM Model: `lstm_model.joblib`  
   - Facebook Prophet Model: fb_prophet_model.joblib

---

This repository contains a Streamlit web application for stock price prediction using historical data. The project integrates multiple time series forecasting models, including ARIMA, SARIMAX, LSTM, and Facebook Prophet, to analyze stock trends and predict future prices.

Project Overview

1. Data Collection

Historical stock price data is collected using the yfinance library.

Users can select a stock symbol and retrieve data for analysis and forecasting.

2. Exploratory Data Analysis (EDA)

Conducted detailed EDA on stock price data, analyzing trends and seasonality.

Visualizations include:

Close Price vs Year

Candlestick Chart (Plotly)

Moving Averages (Plotly)

3. Time Series Forecasting Models

ARIMA & SARIMAX((Not Used in Deployment)

Traditional time series models used to analyze historical patterns and establish benchmark predictions.

Deep Learning & Advanced Forecasting Models (Used in Deployment)

LSTM Model: A Long Short-Term Memory (LSTM) neural network trained on a 10-year dataset to capture complex patterns in stock prices.

Facebook Prophet: A robust time series forecasting model that accounts for trends and seasonality.

4. Deployment

The application is deployed using Streamlit Cloud, allowing users to:

Select a stock and define forecast duration (1 to 30 days)

Choose a prediction model (LSTM or Facebook Prophet)

Visualize forecasts with interactive Plotly graphs

  5.Model Files Used for Deployment

LSTM Model: lstm_model.joblib

Facebook Prophet Model: fb_prophet_model.joblib






****Try the App****

You can try out the Stock Price Prediction App [here](https://hnp-stock-market-prediction-app.streamlit.app/)
