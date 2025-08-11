# 📊 Students Social Media Addiction Analysis

## 1️⃣ Introduction

This project focuses on analyzing Social Media Addiction patterns using Excel and Python.
Social media has become a part of daily life — but excessive usage can lead to addiction and negatively impact productivity, academics, and mental health.
This project analyzes survey data to understand patterns of social media addiction and predicts Addiction Scores using a Decision Tree model.

## 2️⃣ Objectives

1.Analyze usage trends and behavior patterns from survey data.

2.Build an interactive Excel dashboard to visualize KPIs.

3.Predict Addiction Levels using machine learning.

## 3️⃣ Dataset

### Dataset taken from Kaggle.
Source: Survey-based dataset (contains age, usage hours, platform preferences, and self-reported addiction scores).
### Key Fields:
Gender,
Average Daily Usage Hours,
Platform Preference,
Impact on Academic Performance,
Sleep Hours,
Mental Health Score,
Addiction Score (Target variable).

## 4️⃣ Methodology

### Excel Analysis
- Data cleaning and formatting.
  
- Pivot tables for comparative insights.
  
- Dashboard with: [View Excel Dashboard](https://github.com/Ambika3003/Social_Media_Addiction_Analysis/blob/main/images/social_media_addiction_dashboard1.png)

📌 KPIs (Average Addicted Score, % of students affected academically, Students in each level).
📊 Charts (Bar, Line, Pie) for
- Mostly used apps
  
- Addicted score by academic level and gender
  
- Top 10 countries by Usage

### Python Analysis
Libraries Used: pandas, numpy, matplotlib, plotly, seaborn, scikit-learn.
Steps:
- Load & preprocess dataset.
- Perform Exploratory Data Analysis (EDA).
  - Platforms associated with negative academic performance
  - addiction scores variation across Gender
  - Checked correlation between Numerical Columns.
- Train a DecisionTreeRegressor for addiction score prediction.
- Evaluate with R-Squared, MAE, MSE.


## 5️⃣ Key Findings

📈 Correlation: Higher daily usage → higher addiction scores.

📊 HIGH SCHOOL STUDENTS ARE AT MOST RISK

🎯 Decision Tree achieved 94% r2 in Prediction.


## 6️⃣Future Plans

Enlarge the dataset

Add Random Forest or XGBoost models for better prediction.

Integrate screen time logs from devices rather than self-reports.
