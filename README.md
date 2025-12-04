# 📊 Cryptocurrency Market Analysis (Bitcoin vs Ethereum)

## 📌 Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on historical cryptocurrency data for Bitcoin (BTC) and Ethereum (ETH).
The goal is to understand price behaviour, volatility patterns, trading volume trends, and how these two major cryptocurrencies differ over time.

This analysis helps identify:

1. Trend movements

2. Volatility cycles

3. Correlations between price metrics

4. Daily return behaviour

5. Market momentum using moving averages

## 🛠 Tech Stack

1. Python

2. Pandas

3. NumPy

4. Matplotlib

5. Seaborn

## 📁 Dataset

The dataset contains historical price data for BTC and ETH, including:

1. Date

2. Open

3. High

4. Low

5. Close

6. Volume

Data was pre-cleaned using Pandas for consistency and accuracy.

## 🧹 Data Cleaning & Preparation

1. Converted date column to datetime

2. Sorted data chronologically

3. Removed duplicates

4. Checked for null values

5. Ensured numeric consistency

6. Created new engineered features

## 🧪 Feature Engineering

This project adds several financial features:

Daily Returns
daily_return = close_price.pct_change()

Price Range (High – Low)

7-day Moving Average (MA-7)

30-day Moving Average (MA-30)

7-day Rolling Volatility

30-day Rolling Volatility

These features help analyze trends and market momentum.

## 📈 Visualizations

The project includes the following visual plots:

✔ Closing Price Comparison (BTC vs ETH)

Shows long-term trends and price movements.

✔ Daily Returns

Highlights volatility and high-risk price swings.

✔ Trade Volume

Shows how trading activity evolves over time.

✔ Price Range Distribution

Displays how much BTC and ETH prices fluctuate intraday.

✔ Moving Averages (MA-7 & MA-30)

Identifies trend reversals and momentum shifts.

✔ Rolling Volatility

Analyzes market risk and instability.

✔ Correlation Heatmaps

Shows relationships between price metrics (open, high, low, close, volume).

## 🧠 Key Insights

* Ethereum shows greater intraday volatility than Bitcoin, resulting in more aggressive price swings.

* Bitcoin maintains smoother long-term stability compared to ETH.

* Daily returns for both cryptocurrencies fluctuate heavily, confirming high market risk.

* Price components (open/high/low/close) are strongly correlated, showing typical financial structure.

* Volume has weaker correlation with price, suggesting sentiment-driven market moves.

* Moving averages help identify bullish/bearish periods based on MA-7 and MA-30 crossovers.

## 📌 Conclusion

This project gives a comprehensive understanding of cryptocurrency behaviour using statistical and visual analysis.
It highlights how BTC and ETH differ in stability, price fluctuations, and long-term trends — useful for anyone studying financial markets, risk, or time-series data.

## 🚀 How to Run the Project
pip install pandas numpy matplotlib seaborn

python cryptocurrency_eda.py
