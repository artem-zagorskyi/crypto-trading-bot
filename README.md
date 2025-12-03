# Crypto Trading Bot
This project implements a cryptocurrency trading bot built around deep learning–based price prediction.
The bot analyzes pre-collected OHLCV market data and uses several advanced neural network architectures to forecast future price movements. Based on these predictions, it generates trading decisions that can later be integrated with any exchange execution layer.

## 📌 Key Features

- **Deep Learning Models for Price Prediction**  
  Includes several architectures such as **LSTM**, **EMD-LSTM**, **Deep LSTM + MLP**, **PatchTST**, and **Crossformer**.  
  All models are trained and tested on historical OHLCV data to evaluate forecasting accuracy.

- **Hyperparameter and Architecture Search**  
  The project supports systematic exploration of model architectures and hyperparameters to identify the most effective configurations.

- **Focused on BTC and ETH Trading**  
  The bot is currently designed to analyze and generate trading decisions for **Bitcoin (BTC)** and **Ethereum (ETH)**.

## 📊 Data

The project uses pre-collected **daily OHLCV candles** sourced from **Binance**, covering the years **2018–2025**.  
