📊 Stock Forecasting Application

  > This repository contains a Streamlit-based stock forecasting application built to analyze, visualize, and predict stock performance. It features stock information, price prediction using ARIMA models, return and risk analysis via CAPM, and technical indicator-based insights for smarter investment decisions.

🚀 Features:

  📌 Stock Information:
  
       > Get an overview of any stock with business summary, sector classification, and key financial metrics.

🔮 Stock Price Prediction:

       > Predicts the next 30 days of closing prices using historical data and ARIMA time series models.

📈 Stock Analysis with Indicators:
  > Visual analysis powered by technical indicators including:

        RSI (Relative Strength Index)

        MACD (Moving Average Convergence Divergence)

        Simple & Exponential Moving Averages

📉 CAPM Calculations:
 > Compute expected return and beta values using the Capital Asset Pricing Model.


🧰 Requirements:
 > To run this application, install the following dependencies:
    pip install streamlit pandas yfinance plotly pandas_ta numpy scikit-learn statsmodels
  Or, use a requirements.txt to streamline setup.

📁 File Structure:

> Trading_App.py – Main Streamlit app entry point that interfaces with users.

> Stock_Prediction.py – Contains stock prediction logic using ARIMA and Linear Regression models.

> Stock_Analysis.py – Provides detailed technical analysis (RSI, MACD, moving averages).

> model_train.py – Utility functions for training and evaluating the stock prediction models.

> plotly_figure.py – Functions to generate and display interactive charts with Plotly.

> CAPM_Return.py – Calculates the expected return using the Capital Asset Pricing Model (CAPM).

> CAPM_Beta.py – Computes the beta value of a stock for CAPM calculations.

> requirements.txt – Python dependencies needed for the application to function.


⚙️ How to Run
 Clone the repository:
   > git clone https://github.com/PMdFaizal/Stock_Forecasting_Application.git

Navigate into the project directory:
 > cd Stock_Forecasting_Application

Install dependencies:
 > pip install -r requirements.txt

Start the Streamlit app:
 > streamlit run Trading_App.py

The app will open in your default web browser.

