# Time-Series Forex ML Research with Realistic Market Frictions

## Overview
This project investigates machine learning methods for Forex time-series forecasting while explicitly accounting for real-world trading execution constraints.

Unlike traditional studies that assume frictionless markets, this project integrates realistic market frictions such as spread, slippage, and execution delays to evaluate how they impact both rule-based and machine learning-based trading strategies.

The focus is on understanding whether predictive models remain effective once deployed in realistic market conditions.

---

## Research Question
Do machine learning models maintain their predictive and trading advantage over simple rule-based strategies when realistic market execution constraints are introduced?

---

## Objectives
- Implement a baseline moving average crossover strategy
- Develop a machine learning model for time-series forecasting
- Simulate realistic market conditions (spread, slippage, execution delay)
- Evaluate and compare strategy performance under ideal vs real conditions
- Analyze robustness of ML models in non-ideal environments

---

## Methodology

### 1. Baseline Strategy
- Moving Average crossover strategy
- Simple rule-based decision system

### 2. Machine Learning Model
- Feature-based forecasting model
- Time-series feature engineering (returns, volatility, lag features)
- Supervised learning for direction/return prediction

### 3. Market Frictions Layer
- Bid/ask spread modeling
- Slippage simulation
- Execution delay approximation
- Transaction cost incorporation

### 4. Evaluation Framework
- Backtesting engine
- Performance under:
  - Ideal conditions (no friction)
  - Realistic market conditions

---

## Evaluation Metrics
- Total return
- Sharpe ratio
- Maximum drawdown
- Performance degradation due to market frictions

---

## Data
- EURUSD historical time-series data (M1 timeframe)

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib

---

## Project Status
This project is under active development. Future work includes refining the machine learning models, improving feature engineering, and extending the evaluation framework.

---

## Key Contribution
This project focuses on bridging the gap between machine learning-based trading models and real-world market execution constraints, highlighting the importance of realistic assumptions in financial modeling.
