# Option-Pricing-with-Convolutional-Kolmogorov-Arnold-Networks
Indian Stock Data Collection & Feature Engineering

This project automates the collection of historical stock data for **NIFTY 50 companies** using the `yfinance` API and generates a comprehensive set of technical indicators. The resulting dataset is suitable for use in **option pricing**, **stock forecasting**, or **financial modeling**.

## Key Features

-  Real-time data fetching from Yahoo Finance via `yfinance`
-  Flexible date range and ticker selection
-  Calculation of essential technical indicators:
  - Rolling Mean & Standard Deviation
  - Relative Strength Index (RSI)
  - MACD (Moving Average Convergence Divergence)
  - Bollinger Bands
-  Export of cleaned, feature-rich datasets for downstream ML models

##  Technologies Used

- Python 3.x
- `yfinance` – financial data API
- `pandas`, `numpy` – data manipulation
- `ta` – technical analysis indicators
- `matplotlib`, `seaborn` – visualization (optional)

##  Project Structure
stock-feature-engineering/
├── data/
│ └── nifty_50_features.csv # Final engineered dataset
├── notebooks/
│ └── stock_data_feature_engineering.ipynb
├── README.md
└── requirements.txt



