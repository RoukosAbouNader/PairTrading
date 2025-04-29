# 📈 Pair Trading Strategy Using Rolling Correlation

This Jupyter notebook implements a **pair trading strategy** using **Apple (AAPL)** and the **S&P 500 index**. The strategy relies on **rolling correlation** to identify trading signals and simulate trade decisions based on historical data.

## 📊 Project Overview

- **Objective:** Design and backtest a market-neutral pair trading strategy.
- **Assets:** Apple (AAPL) and S&P 500.
- **Methodology:**
  - Calculate rolling correlation between the two assets.
  - Generate buy/sell signals based on correlation thresholds.
  - Simulate trades and calculate profits.
- **Tools Used:** Python, Pandas, Matplotlib, NumPy, Backtesting.py

## 🔧 Main Components

- **Data Loading and Cleaning:** Reads CSV files with historical price data.
- **Rolling Correlation Analysis:** Measures 20-day correlation between AAPL and SP500.
- **Trading Logic:**
  - Enter a long/short position if correlation exceeds defined thresholds.
  - Exit when correlation reverts.
- **Backtesting Engine:** Simulates trades and tracks equity curve.
- **Visualization:** Plots price charts, signals, and performance over time.

## 📂 Files

- `PairTrading.ipynb`: The main notebook containing strategy logic and results.
- `apple.csv`, `sp500.csv`: (Optional) Your historical stock data files if not already embedded.

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib backtesting
