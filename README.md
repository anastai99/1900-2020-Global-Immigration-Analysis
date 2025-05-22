# 1900-2020-Global-Immigration-Analysis


# 🌍 Global Emigration Outlook (1990–2045)

This project explores global emigration trends from 1990 to 2020 and forecasts future migration flows through 2045 using linear regression. It is based on publicly available data and focuses on long-term patterns in international migration.

---

## 📁 Dataset

- **Source:** [Kaggle - Global Emigration Trends 1990–2020](https://www.kaggle.com/datasets/shreyasur965/global-emigration-trends-1990-2020)
- **License:** CC0-1.0
- **File Used:** `total-number-of-emigrants.csv`
- **Columns:**
  - `Entity` — Country name
  - `Year` — Year of observation
  - `Total number of emigrants` — Total number of people emigrated from that country in that year

---

## 🔍 Project Goals

### 📊 Part 1: Trend Analysis
- Aggregated global emigration data across all countries.
- Visualized the trend from **1990 to 2020**.
- Identified whether migration is increasing or decreasing globally.

### 🤖 Part 2: Predictive Modeling
- Built a **linear regression model** to project future emigration trends.
- Forecasted migration flows for the years **2025, 2030, 2035, 2040, and 2045**.

---

## 📈 Key Insights

- Global emigration has shown a generally increasing trend from 1990 to 2020.
- Based on the linear model, emigration is projected to continue increasing significantly:
  - **2025:** ~2.56 billion emigrants
  - **2045:** ~3.34 billion emigrants

> ⚠️ These predictions are based on a **simplified linear model** and may overestimate long-term trends due to compounding effects. Future models could be improved with nonlinear methods or additional features (e.g., conflicts, climate change, policy shifts).

---

You can find the code in the .ipynb file

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/anastai99/global-emigration-outlook.git
   cd global-emigration-outlook
