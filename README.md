# XAUUSD Session Analysis

A Python data analysis and machine learning project examining whether London 
session behavior contains predictive signal for the subsequent New York session 
direction on spot Gold (XAUUSD). Built using 5 years of real m5 OHLCV data 
(2021-2026) from Dukascopy, stored in a PostgreSQL database.

## Files
`final_project.ipynb` - EDA, feature engineering, statistical validation, and XGBoost classification + assessment

## Data
- Source: Dukascopy (via dukascopy-node + custom ETL pipeline)
- Coverage: 2021-01-03 - 2026-07-19 (~391,000 5-minute OHLC candles)
- Storage: DigitalOcean PostgreSQL
