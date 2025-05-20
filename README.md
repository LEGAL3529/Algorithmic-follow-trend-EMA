# EMA Strategy on Nasdaq Futures (NQ) (LimexQuant Course Project)

This repository contains a simple trend-following strategy based on Exponential Moving Averages (EMA), applied to continuous NQ futures data.

## 📈 Strategy Description

- **Logic:** Enter long when EMA(20) > EMA(50), exit when reversed
- **Data:** Cleaned 1D OHLCV data from NQ futures (`NQ.csv`)
- **Visualization:** Jupyter Notebook with full signal logic, equity curve, and performance stats
