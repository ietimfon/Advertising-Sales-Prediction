# Advertising-Sales-Prediction
---

## Table of Contents
- [Overview](📌#overview)
- [Dataset](📂#dataset)
- [Tools](🛠️#tools)
- [Key Steps](#key-steps)
- [Key Insights from EDA](📊#key-insights-from-EDA)
- [Conclusion](📝#conclusion)


### 📌 Overview
This project analyzes the relationship between advertising expenditures (TV, Radio, Newspaper) and product sales using Polynomial Regression. The goal is to predict future sales based on historical advertising budgets.


### 📂 Dataset
The dataset contains advertising budgets and corresponding sales for a product:

#### Features (Input):
- TV: Advertising budget spent on TV (in thousands)
- Radio: Advertising budget spent on Radio
- Newspaper: Advertising budget spent on Newspaper

#### Target (Output):
- Sales: Product sales (in thousands)


### 🛠️ Tools
- Python 3.7+
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn


### Key Steps
- ✅ Data Exploration – Statistical analysis & visualizations
- ✅ Data Preprocessing – Handling missing values, feature engineering
- ✅ Model Training – Polynomial Regression for sales prediction
- ✅ Evaluation – Metrics (R², MSE) & model performance
- ✅ Prediction – Future sales forecasting


### 📊 Key Insights from EDA
1. TV ads have the strongest correlation with sales (0.80)
2. Newspaper ads have the weakest impact (0.20)
3. Radio ads show moderate influence (0.55)
4. Polynomial Regression (Degree = 2) performed well with an R² score of 0.99 on training data.

#### Feature Importance (Impact on Sales)
|Feature|Correlation with Sales|
|-------|----------------------|
|TV	|0.80 (Strong)|
|Radio|	0.55 (Moderate)|
|Newspaper|0.20 (Weak)|


### 📝 Conclusion
- TV advertising has the highest impact on sales
- Newspaper ads contribute the least and could be optimized for cost efficiency
- Polynomial Regression outperforms Linear Regression due to non-linear ad-sales relationships
