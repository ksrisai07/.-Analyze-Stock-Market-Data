# 📊 Stock Market Data Analysis Dashboard

This project performs exploratory data analysis (EDA) and visualization on historical stock market data for multiple assets including **AMZN**, **DPZ**, **BTC**, and **NFLX**. It includes data cleaning, statistical summary, correlations, and return distribution analysis.

## 🧠 Overview

This project helps visualize and understand the behavior and relationships between selected assets using Python. It performs:

- Data quality checks (missing values, unique values)
- Summary statistics & transposed overview
- Trend analysis & correlation heatmaps
- Daily returns & distribution analysis
- Rolling average visualization
- Cumulative returns and area plots

## 📂 Sample Insights

### 🔍 Missing Values

No missing values detected across columns.


---

### 📈 Summary Statistics

Key statistical metrics:

| Asset | Mean | Std Dev | Min | Max |
|-------|------|---------|-----|-----|
| AMZN | 821.54 | 518.44 | 248.23 | 2039.51 |
| DPZ  | 146.77 | 72.19 | 51.19 | 298.64 |
| BTC  | 2421.47 | 3310.89 | 69.66 | 18972.32 |
| NFLX | 147.67 | 107.64 | 29.46 | 418.97 |

---

## 📊 Visualizations

All charts are generated using **Matplotlib** and **Seaborn**.

### 📉 Price Trends Over Time

- Multi-line plot showing daily closing prices.

### 🔥 Correlation Heatmap

- Shows how closely each stock is correlated with the others.

### 📈 Daily Return Distributions

- Kernel Density Estimates of daily returns for each asset.

### 📦 Box Plot of Price Distributions

- Quick view of outliers, medians, and spread.

### 🔁 30-Day Rolling Averages

- Smoothed line chart to highlight trends.

### 📈 Cumulative Returns

- Line & area plots of how a $1 investment would have grown.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Jupyter Notebook

## 🚀 Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/stock-analysis-project.git
   cd stock-analysis-project
