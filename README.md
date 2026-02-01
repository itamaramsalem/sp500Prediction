# S&P 500 Prediction

Machine learning models for predicting next-day S&P 500 price direction using historical market data from Yahoo Finance.

## Notebooks

- **spLogReg_prediction.ipynb** — Logistic Regression with StandardScaler and rolling feature engineering
- **spRandomForest_prediction.ipynb** — Random Forest classifier with probability-threshold tuning

Both notebooks use a walk-forward backtesting approach (expanding training window) and evaluate with precision, AUC, and ROC curves.

## Setup

```bash
pip install yfinance pandas matplotlib scikit-learn
```

Run each notebook top-to-bottom to fetch live data and generate results.
