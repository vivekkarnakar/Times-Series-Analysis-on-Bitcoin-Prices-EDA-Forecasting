# Times-Series-Analysis-on-Bitcoin-Prices-EDA-Forecasting

## 📌 Project Overview
This project involves exploratory data analysis and forecasting of Bitcoin prices using time series techniques. The aim is to understand the trends and patterns in historical data and predict future prices using Times Series Models. A thorough Exploratory Data Analysis (EDA) was conducted, MA and ARIMA models were used and Grid Search was used to fine-tune the ARIMA model's hyperparameters. RSME is used to avaluate the prediction.

## 🔍 Objectives
Perform detailed Exploratory Data Analysis (EDA) on Bitcoin price data

Forecast Bitcoin prices using MA and ARIMA models

Use Grid Search to optimize ARIMA model parameters

Evaluate the model’s performance using RMSE

## 📊 Project Workflow
<b>Data Collection:</b><br>
-- Obtain Bitcoin price data<br>

<b>Data Preprocessing:</b><br>
-- Check for missing values<br>
-- Convert Columns to approreiate data types<br>
-- Handled outliers and scaled data if necessary<br>

<b>Exploratory Data Analysis (EDA):</b><br>
-- Calculate Moving average<br>
-- Perform Classical Decomposition<br>
-- Check for Stationarity<br>
-- Plot ACF and PACF<br>

<b>Modeling & Forecasting:</b><br>
-- Applied Moving Average (MA) model for forecasting<br>
-- Implemented ARIMA model with Grid Search for (p,d,q) parameter tuning<br>
-- Selected best model based on lowest RMSE<br>

<b>Evaluation:</b><br>
Final ARIMA model achieved an RMSE of 1584, indicating a reasonably accurate forecast<br>

## 📈 Key Findings
Bitcoin prices show high volatility and long-term upward trends

ARIMA model, after parameter tuning, outperformed the MA model in terms of forecasting accuracy

Visualizations helped identify trends, seasonality, and model performance

## 📂 Files
📄Time Series Analysis of Bitcoin Prices.ipynb ----> # Main code file, containes all code for EDA and forecasting 

📄Historical Bitcoin Data.csv ----> # CSV file containing Bitcoin prices data

