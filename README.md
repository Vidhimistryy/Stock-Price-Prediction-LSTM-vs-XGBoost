# Stock Price Prediction: LSTM vs XGBoost

A comparative time-series modeling study using historical market data, an LSTM neural network, and an XGBoost regressor. The goal is to make the modeling choices and limitations visible while comparing two different approaches to a forecasting problem.

## What the notebook demonstrates

The experiment downloads historical data with `yfinance`, prepares sequences for an LSTM, creates an XGBoost regression workflow, evaluates predictions with error metrics, and visualizes the comparison. Tickers can be adapted for NSE or US markets after checking data availability and provider terms.

## Reproducibility notes

Forecasting results depend on the date range, ticker, data adjustments, feature engineering, random seeds, lookback window, and train/test design. Avoid random splits for time-series evaluation and document every experiment configuration before comparing models.

## Responsible-use disclaimer

This repository is for educational research. It does not provide investment advice, personalized financial recommendations, trading signals, or guarantees of future returns.
