# Trader Behavior Analysis Based on Bitcoin Market Sentiment

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

The objective is to identify patterns between market sentiment and trading outcomes, helping traders and institutions develop sentiment-aware trading strategies.

---

## Datasets

### 1. Historical Trader Data

Contains:

* Account
* Coin
* Execution Price
* Size USD
* Side
* Closed PnL
* Fee
* Timestamp

### 2. Bitcoin Fear & Greed Index

Contains:

* Date
* Sentiment Classification
* Fear & Greed Score

Sentiment Categories:

* Extreme Fear
* Fear
* Neutral
* Greed
* Extreme Greed

---

## Methodology

### Data Preprocessing

* Converted timestamps into datetime format
* Extracted trading dates
* Merged trading records with sentiment data using date

### Analysis Performed

* Profitability Analysis
* Win Rate Analysis
* Trading Volume Analysis
* Buy vs Sell Behavior
* ROI Analysis
* Top Trader Analysis
* Statistical Significance Testing

### Statistical Test

Kruskal-Wallis Test was used to determine whether profitability differs significantly across sentiment groups.

---

## Key Findings

### Profitability by Sentiment

| Sentiment     | Average PnL |
| ------------- | ----------- |
| Extreme Greed | 67.89       |
| Fear          | 54.29       |
| Greed         | 42.74       |
| Extreme Fear  | 34.54       |
| Neutral       | 34.31       |

### Insights

* Extreme Greed produced the highest average profit per trade.
* Fear periods generated the largest cumulative profits.
* Trading behavior varies significantly across sentiment regimes.
* Market sentiment has measurable influence on trader performance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---


## Future Improvements

* Machine Learning-based Profit Prediction
* Sentiment-aware Trading Signals
* Risk-adjusted Return Analysis
* Coin-specific Sentiment Impact Study

---

## Author

Akshith Avunuri
Data Science Internship Assignment
