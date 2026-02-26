# Premier League Spending vs Performance Analysis

## Overview

This project analyzes the relationship between transfer spending and league performance in the English Premier League across five seasons (2018–19 to 2022–23).

The goal is to evaluate whether financial investment meaningfully predicts competitive success.

---

## Business Questions

- Does higher transfer spending lead to more league points?
- Does net spending improve predictive power?
- Which clubs outperform relative to spending expectations?
- Is spending a strong predictor of league position?

---

## Data Sources

- Match-level results: football-data.co.uk  
- Transfer spending data: Transfermarkt (Income & Expenditures tables)

Five full seasons were aggregated into a unified dataset (100 club-season observations).

---

## Methodology

- Match-level aggregation to season-level performance metrics  
- Financial data cleaning and normalization (currency → numeric millions)  
- Multi-season dataset merging  
- Correlation analysis  
- Linear regression modeling  
- Residual-based efficiency evaluation  

---

## Key Results

- Transfer spending explains only ~5–6% of variation in league points (R² ≈ 0.06).
- Net spending shows negligible predictive power.
- Several clubs significantly outperformed spending-based expectations.
- Financial investment alone does not determine league success.

---

## Tools Used

- Python  
- pandas  
- seaborn  
- scikit-learn  
- matplotlib  