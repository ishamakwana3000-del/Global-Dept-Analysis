# Global Sovereign Debt Analysis and Forecasting

## Project Overview

This project analyzes global sovereign debt and fiscal-space indicators using World Bank data. The objective is to identify debt trends, compare countries, detect outliers, and forecast future debt values using machine learning.

---

# Dataset

Source: World Bank Fiscal Space Dataset

Dataset contains:
- Country names
- Debt indicators
- Time periods
- Debt values
- Fiscal metrics

---

# Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

## 1. Data Cleaning
- Removed null values
- Converted columns to numeric
- Filtered debt-related indicators

## 2. Exploratory Data Analysis (EDA)
- Global debt trend analysis
- Top debt countries analysis
- Country comparison
- Debt distribution analysis
- Outlier detection

## 3. Data Visualization
Created visualizations using:
- Line plots
- Bar charts
- Histograms
- Scatter plots
- Boxplots
- Dashboard subplots

## 4. Machine Learning
Used Linear Regression for:
- Debt prediction
- Future forecasting

---

# Key Analyses Performed

## Global Debt Trend
Analyzed how sovereign debt changes over time globally.

## Top 10 Debt Countries
Identified countries with highest average debt values.

## Country Comparison
Compared debt trends between India, USA, and China.

## Debt Distribution
Studied spread and frequency of debt values.

## Outlier Detection
Detected extreme debt observations using boxplots.

---

# Sample Visualizations

## Global Debt Trend
![Trend](images/trend.png)

## Dashboard
![Dashboard](images/dashboard.png)

---

# Machine Learning Model

Model Used:
- Linear Regression

Target Variable:
- OBS_VALUE

Feature Used:
- TIME_PERIOD

---

# Project Structure

```text
Global-Debt-Analysis/
│
├── data/
│   └── WB_CCDFS.csv
│
├── notebooks/
│   └── debt_analysis.ipynb
│
├── images/
│   ├── trend.png
│   └── dashboard.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Future Improvements

- Streamlit dashboard deployment
- Power BI integration
- Deep learning forecasting
- Interactive visualizations

---

# Conclusion

This project demonstrates:
- Data cleaning
- Exploratory data analysis
- Visualization
- Dashboarding
- Machine learning forecasting

using real-world fiscal and sovereign debt data.
