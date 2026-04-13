Prediction
This repository contains two complementary machine learning projects applied to financial markets:

Arbitrage.ipynb – A comprehensive and advanced statistical arbitrage pipeline with ML models, feature engineering, reinforcement learning, GAN-based synthetic data, and full model comparison.
stock_market_predictor.ipynb – A stock price prediction workflow demonstrating classical ML and time-series modeling.
These notebooks showcase real-world quantitative finance techniques using deep learning, reinforcement learning, synthetic data generation, and advanced technical indicators.

📘 Project Components
1. Arbitrage.ipynb – FULL Statistical Arbitrage Pipeline
A highly detailed quantitative finance workflow including:

Hybrid deep learning models (CNN-LSTM, Attention-LSTM)
Reinforcement learning trading: Deep Q-Network (DQN)
Synthetic data generation using GAN and WGAN-GP
Full model comparison dashboard
Return and performance evaluation
Regime detection + volatility features
Execution-ready arbitrage insights
2. stock_market_predictor.ipynb – Stock Forecasting
A compact notebook demonstrating:

Historical stock data extraction
Exploratory data analysis (EDA)
ML model development for prediction
Visualization of forecast vs real values
Financial time-series preprocessing
🧠 Advanced Model Insights (Arbitrage Notebook)
Best Classification Model
CNN-LSTM Hybrid
Accuracy: 70.2%
Strong sequence learning with spatial + temporal patterns.
Best Trading Performance
DQN Trading Agent
Returns: 42.98%
Learns buy/hold/sell behavior through reward optimization.
Most Advanced Architecture
Attention-LSTM
Integrates self-attention for interpretability and dynamic weighting.
Synthetic Data Quality
WGAN-GP produces realistic financial sequences.
Gradient penalty = improved stability.
🎨 Generative Models Comparison
Vanilla GAN
Generator params: 997,420
Discriminator params: 964,609
Good synthetic generation but unstable at times.
WGAN-GP
Generator params: 715,308
Critic params: 318,465
Superior sequence realism
Improved stability due to Wasserstein loss + gradient penalty
🔧 Feature Engineering Summary (79 Features)
Technical Indicators
RSI, MACD, ATR, Williams %R, Stochastic Oscillator

Volatility
Volatility clustering, percentile features, rolling variance

Momentum
Rate of Change (ROC), acceleration, trend indicators

Market Microstructure
Bollinger Bands, spreads, z-score bands, threshold features

Temporal
Day of week, month, quarter, holiday effects, seasonality

Statistical
Rolling correlations, covariance, rolling beta, z-scores

🚀 Project Achievements
Basic Statistical Arbitrage Strategy: –5.26%
CNN-LSTM Accuracy: 70.2%
DQN trading returns: 42.98%
GAN & WGAN-GP synthetic series generation
Attention-LSTM model implemented
Full model comparison dashboard
