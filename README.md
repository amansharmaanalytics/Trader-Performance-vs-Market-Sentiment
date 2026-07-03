# 📈 Trader Performance vs Market Sentiment Analysis

## Primetrade.ai – Data Science Internship Assignment

### 📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

The objective is to determine whether trader profitability and trading behavior change during Fear and Greed market conditions.

---

## 🎯 Objectives

- Clean and preprocess two datasets
- Merge market sentiment with trader activity
- Analyze trader performance
- Identify behavioral changes
- Generate actionable trading insights

---

## 📂 Dataset

### 1. Bitcoin Fear & Greed Index

Contains

- Date
- Fear / Greed Classification

### 2. Hyperliquid Historical Trader Data

Contains

- Account
- Coin
- Execution Price
- Trade Size
- Side (Buy/Sell)
- Closed PnL
- Timestamp
- Position Information

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Key Metrics

- Daily PnL
- Win Rate
- Average Trade Size
- Trade Count
- Long vs Short Ratio
- Trader Segmentation

---

## 📈 Analysis Performed

- Data Cleaning
- Missing Value Analysis
- Duplicate Check
- Date Alignment
- Dataset Merge
- Feature Engineering
- Exploratory Data Analysis
- Sentiment Analysis
- Trader Segmentation

---

## 💡 Key Insights

- Trader profitability differs between Fear and Greed periods.
- Trading frequency changes with market sentiment.
- Larger position sizes are more common during Greed periods.
- Consistently profitable traders generally avoid excessive trading.

---

## 🚀 Strategy Recommendations

### Strategy 1

Reduce position size during Fear periods to minimize downside risk.

### Strategy 2

Avoid overtrading during Greed periods despite increased market activity.

---

## 📁 Repository Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── Trader_Performance_vs_Sentiment.ipynb
├── README.md
├── requirements.txt
├── daily_trader_metrics.csv
├── merged_dataset.csv
└── charts/
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Open

```
Trader_Performance_vs_Sentiment.ipynb
```

Run all cells.

---

## 👨‍💻 Author

**Aman Sharma**

Business Analytics | Data Analytics | Python | SQL | Power BI
