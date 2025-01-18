## Customer Churn Analysis
This repository contains an in-depth analysis of customer churn using Python. The project leverages a variety of data exploration, visualization, and preprocessing techniques to identify key factors influencing customer attrition. Insights from the analysis can guide strategies to improve customer retention.
## Project Overview
Customer churn is a critical metric for any subscription-based business. This analysis explores the Customer Churn dataset to:
- Understand overall churn trends.
- Identify key factors contributing to customer attrition.
- Provide actionable insights to improve retention strategies.
### Key tools and libraries used:
- Pandas: For data manipulation and preprocessing.
- Matplotlib and Seaborn: For data visualization.
- NumPy: For numerical operations.
## Key Features
1. Data Preparation
- Cleaned missing values in the dataset.
- Converted categorical variables into interpretable formats (e.g., converting binary indicators for senior citizens into "Yes/No").
2. Exploratory Data Analysis (EDA)
- Generated descriptive statistics and visualized churn trends across:
-- Contract Types: Month-to-month contracts are associated with higher churn rates.
-- Services: Lack of optional services like OnlineSecurity, OnlineBackup, and TechSupport correlates with higher churn.
-- Payment Methods: Customers using Electronic Check are more likely to churn.
3. Visualizations
- Pie Chart: Showcased overall churn proportion (26.54% churn rate).
- Count Plots: Explored categorical factors like PhoneService, InternetService, and PaymentMethod in relation to churn.
- Subplots: Examined patterns across multiple services to uncover trends.
## Insights and Recommendations
### Insights
1. Customers with month-to-month contracts have a churn rate of approximately 42%.
2. Electronic Check users show a 46% churn rate, the highest among payment methods.
3. Lack of optional services like OnlineSecurity and TechSupport significantly increases the likelihood of churn.
### Recommendations
1. Incentivize customers to move to long-term contracts (1-year or 2-year) with discounts or rewards.
2. Provide tailored offers for Electronic Check users to shift to alternative payment methods.
3. Promote optional service subscriptions through trials or bundled discounts to reduce churn.
## Dependencies
- Python 3.7+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- numpy
