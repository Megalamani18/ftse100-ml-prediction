# ftse100-ml-prediction
Applied supervised machine learning to financial time series data. Features included momentum indicators (RSI, MACD), trend signals (SMA, EMA crossovers), and volatility measures. Used walk-forward train/test splitting to prevent data leakage, and addressed class imbalance with balanced class weighting across models.

# FTSE 100 Market Direction Predictor

Predicting daily FTSE 100 market direction (up/down) using 
technical indicators and machine learning.

## Tools Used
- Python, pandas, numpy, yfinance
- scikit-learn, XGBoost
- matplotlib, seaborn

## Technical Indicators
- SMA, EMA (20 & 50 day)
- RSI (14), MACD, Bollinger Bands
- Rolling Volatility
- ## Models & Results
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | ~47.4%     |
| Random Forest       | ~47.2%    |
| SVM                 | ~55.6%    |
| XGBoost             | ~44.6%    |

## Data
FTSE 100 daily OHLCV data from 2018–present via yfinance.
