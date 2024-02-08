# StockSense: Stock Analysis and Forecasting App

## Overview

StockSense is a user-friendly application built in Python using Streamlit and NLTK. It combines Sentiment Analysis and Time Series Forecasting techniques to provide insights into stock news, sentiment trends, and forecasts. The app is designed for informed decision-making in the dynamic world of stock trading.

## Techniques Used

1. **Sentiment Analysis:**
   - Utilizes the TextBlob library to analyze sentiment in stock news headlines.
   - Classifies sentiments as Positive, Negative, or Neutral.
   - Provides a quick overview of the overall sentiment trends related to the entered stock symbol.

2. **Time Series Forecasting:**
   - Implements two forecasting models: ARIMA (AutoRegressive Integrated Moving Average) and ETS (Exponential Smoothing State Space Model).
   - Forecasts future stock prices based on historical closing prices.
   - Allows users to customize the forecast period for up to 365 days.

## Tools Used

- **Python Libraries:**
  - Streamlit: For creating a user-friendly web app.
  - NLTK (Natural Language Toolkit): For text processing and sentiment analysis.
  - yfinance: For retrieving historical stock data.
  - Matplotlib: For data visualization and plotting.

## How to Run

1. **Install the Dependencies:**
2. **Run the App:**
   - Open a console or terminal window.
   - Navigate to the project directory.
   - Run the command: `streamlit run app.py`
   - Enter the stock symbol and click the "Submit" button to view stock news, sentiment, historical trend, and forecast.

