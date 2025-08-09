# AI-Portfolio-Management
CVaR-based AI-enhanced portfolio optimization with ML/DL models for equity investment strategies.

# AI-Enhanced Portfolio Optimization

This project implements a **risk-aware capital allocation engine** for public equity investments, combining **Conditional Value at Risk (CVaR) optimization** with **machine learning and deep learning forecasting**.

## Features
- CVaR-based portfolio optimization with `cvxpy`
- Forecasting models: XGBoost, LSTM, ARIMA
- Real-time prediction interface with Gradio
- Automated market data pipelines

## Installation
pip install -r requirements.txt

- Usage
1. Place stocks.zip in data/ and unzip.
2. Open notebooks/portfolio_optimization.ipynb.

- Run cells to:
1. Load & clean data
2. Train forecasting models
3. Optimize portfolio
4. Launch Gradio app

- Example Results
Model &	MSE

XGBoost	0.0796

LSTM	0.0003

ARIMA	1.8457
