# Volatility Modeling and Prediction

A comprehensive financial modeling project developed during CentraleSupélec's academic program (June 2024), focusing on volatility estimation, rough volatility modeling, and trading strategy development for SPY (S&P 500 ETF) financial time series.

## 📋 Project Overview

This project explores advanced volatility modeling techniques to predict financial market volatility and develop trading strategies. The implementation combines classical econometric models with cutting-edge rough volatility theory to provide robust volatility forecasts.

### Key Objectives
- Model and predict volatility of SPY financial time series using multiple approaches
- Compare range-based volatility estimators with traditional methods
- Implement rough volatility models for enhanced prediction accuracy
- Develop and backtest trading strategies based on volatility forecasts

## 🔧 Technical Components

### Part I: Volatility Estimation
Implementation of multiple volatility estimators:

- **Close-to-Close Volatility**: Traditional estimators with zero and non-zero drift assumptions
- **Range-Based Estimators**:
  - Parkinson estimator (high-low range based)
  - Garman-Klass estimator (incorporating opening/closing prices)
  - Rogers-Satchell estimator (drift-robust)
  - Yang-Zhang estimator (accounts for opening jumps)

### Part II: Rough Volatility Modeling
Advanced modeling using fractional processes:

- **Rough Fractional Stochastic Volatility (RFSV)** model implementation
- **Fractional Ornstein-Uhlenbeck** process for log-volatility dynamics
- Statistical analysis of volatility regularity and scaling properties
- Monofractality testing and Hurst parameter estimation

### Part III: Trading Strategy Development
Practical application of volatility predictions:

- Long/short position strategies based on volatility signals
- Performance metrics calculation (Sharpe Ratio, Drawdown)
- Risk quantification and strategy optimization
- Backtesting on historical SPY and VXX data

## 📊 Data & Analysis

**Dataset**: SPDR S&P 500 ETF Trust (SPY) daily data from 2000-2013
- Source: Yahoo Finance
- Features: Open, High, Low, Close (OHLC) prices
- Extended analysis period: 1993-2024 for validation

**Key Analytical Features**:
- Statistical comparison of estimator efficiency and precision
- Autocorrelation structure analysis of volatility processes
- Scaling behavior investigation across multiple time horizons
- Empirical validation of rough volatility theoretical predictions

## 🛠️ Technology Stack

- **Python** with scientific computing libraries
- **SciPy** for numerical methods and statistical analysis
- **Time Series Analysis** using ARCH/GARCH models
- **Financial Data Processing** from Yahoo Finance API
- **Statistical Testing** and model validation frameworks

## 📈 Results & Applications

The project provides:
- Comprehensive volatility estimation toolkit
- Validated rough volatility model implementations
- Performance-tested trading strategies
- Statistical framework for volatility model comparison

## 🎯 Academic Context

Developed as part of CentraleSupélec's quantitative finance curriculum, this project demonstrates:
- Advanced mathematical modeling in finance
- Statistical analysis and empirical validation
- Practical application of academic research to trading
- Critical evaluation of competing methodologies

## 🔍 Key Insights

- Range-based estimators significantly outperform close-to-close methods
- Rough volatility models capture long-memory properties better than classical approaches
- Trading strategies benefit from sophisticated volatility prediction models
- Statistical validation is crucial for model selection and parameter estimation

## 📋 Project Guidelines

The complete project specifications and requirements are detailed in the accompanying PDF document `Volatility_prediction_Project-3.pdf`.

---

*This project combines rigorous academic research with practical financial applications, showcasing the intersection of advanced mathematics, statistical analysis, and quantitative finance.*
