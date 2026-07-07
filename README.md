# Exploratory-Data-Analysis-EDA-
Exploratory Data Analysis on the Titanic dataset — CodeAlpha Data Analytics Internship, Task 1. Covers data structure exploration, missing value &amp; outlier detection, univariate/bivariate analysis, and hypothesis testing.

# Titanic Dataset — Exploratory Data Analysis (EDA)

**CodeAlpha Data Analytics Internship — Task 1: Exploratory Data Analysis (EDA)**

## 📌 Overview
This project performs a complete exploratory data analysis on the Titanic
passenger dataset (891 records) to understand what factors were associated
with passenger survival. The analysis follows a structured EDA workflow:
asking meaningful questions, exploring data structure, detecting data
quality issues and anomalies, visualizing trends and patterns, and
statistically testing hypotheses.

## 📂 Files
- `EDA_Titanic.ipynb` — Jupyter notebook with the full analysis, code, and visualizations
- `titanic.csv` — Dataset used for the analysis

## 🔍 What's covered
- Meaningful research questions defined before analysis
- Data structure exploration (shape, dtypes, summary stats)
- Missing value analysis & data quality checks (duplicates, inconsistencies)
- Univariate analysis (distributions of Age, Fare, Class, Sex, Survival)
- Outlier / anomaly detection (Fare, Age)
- Bivariate analysis (Survival vs. Sex, Class, Age, Family Size, Embarked)
- Correlation heatmap
- Hypothesis testing (Chi-square test, t-test, point-biserial correlation)
- Summary of key findings and data issues for further analysis

## 🛠 Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

## 📊 Key Findings
- Sex was the strongest predictor of survival (women survived at a much higher rate, statistically significant).
- Passenger class and fare were strongly linked to survival — wealthier, 1st-class passengers had better odds.
- Small families (2–4 members) had higher survival rates than solo travelers or very large families.
- ~20% of Age values and ~77% of Cabin values were missing, requiring imputation/feature engineering before modeling.

## ✍️ Author
Submitted as part of the CodeAlpha Data Analytics Internship.
