# 📊 Sector-Level Market Stress Analysis

## 📌 Overview
This project analyzes equity market behavior at a **sector level** by aggregating ~2200 stocks and evaluating their internal strength.

Instead of relying only on index-level performance, the analysis focuses on:
- Market participation (breadth)
- Internal volatility (dispersion)
- Momentum trends across multiple timeframes

The goal is to identify **strong, weak, and stressed sectors** using data-driven techniques.

---

## 🎯 Objective
- Analyze sector-wise performance using multiple financial indicators
- Identify hidden weaknesses not visible in index movements
- Detect early signs of sector stress
- Support data-driven decision making in trading and risk analysis

---

## 🗂️ Dataset & Features
The dataset contains sector-level aggregated metrics derived from ~2200 stocks.

Key features include:

- **Returns:** `ret_eq`, `ret_med`
- **Market Breadth:** `pct_positive`
- **Dispersion Metrics:** `dispersion_std`, `dispersion_iqr`
- **Momentum Indicators:**
  - `ret_5d`, `ret_15d`, `ret_30d`
- **Change Metrics:**
  - `index_chg_5d`, `breadth_chg_5d`, `dispersion_chg_5d`
  - `index_chg_15d`, `breadth_chg_15d`, `dispersion_chg_15d`
  - `index_chg_30d`, `breadth_chg_30d`, `dispersion_chg_30d`

These features help capture both **performance and internal structure of sectors**.

---

## ⚙️ Methodology

### 1. Sector Aggregation
Stocks are grouped by sector and analyzed using:
- Equal-weighted returns
- Median returns to reduce outlier impact

---

### 2. Market Breadth Analysis
Measures the percentage of stocks contributing positively.

**Interpretation:**
- High breadth → strong participation
- Low breadth → weak or narrow rallies

---

### 3. Dispersion Analysis (Risk Indicator)
Captures variation in stock performance within a sector.

**Interpretation:**
- High dispersion → higher uncertainty and risk
- Low dispersion → stable sector movement

---

### 4. Momentum Analysis
Evaluates short- and medium-term trends using:
- 5-day, 15-day, and 30-day returns

---

## 🚨 Stress Identification Framework
A sector is classified as **stressed** when:
- Returns are negative
- Market participation (breadth) is weak
- Dispersion is elevated

This helps identify:
- Fragile rallies
- Hidden weaknesses
- Early warning signals in the market

---

## 📈 Key Insights
- Strong sector returns with weak breadth indicate **unsustainable rallies**
- High dispersion suggests **internal disagreement and volatility**
- Momentum divergence signals **trend instability**
- Sector-level analysis provides deeper insights than index-level data

---

## 💻 Tech Stack
- Python
- Pandas / NumPy
- DuckDB (SQL-based querying)
- Jupyter Notebook

---

## 🚀 Use Cases
- Sector rotation strategies
- Risk monitoring and early warning systems
- Portfolio allocation decisions
- Market sentiment analysis

---

## 📌 Conclusion
This project demonstrates how combining **returns, breadth, and dispersion** provides a deeper understanding of market behavior.

It emphasizes:
- Looking beyond index performance
- Understanding internal market dynamics
- Identifying early signs of sectoral stress

---


