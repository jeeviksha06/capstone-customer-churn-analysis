# Capstone Project: Customer Churn Analysis & Retention Strategy

## Business Problem
The company is experiencing customer churn, impacting revenue 
and growth. This project analyzes customer data to identify 
key churn drivers and provide actionable retention strategies.

## Project Objectives
- Identify factors contributing to customer churn
- Quantify the impact of contract type and tenure on churn
- Provide data-driven, actionable business recommendations

## Dataset
- Source: customer_churn.csv
- Size: 500 customers, 9 features
- Features: Tenure, MonthlyCharges, TotalCharges, Contract, 
  PaymentMethod, PaperlessBilling, SeniorCitizen, Churn

## Setup & Installation
1. Install Python 3.x
2. Install required libraries:
pip install pandas numpy scipy matplotlib seaborn jupyter
3. Clone this repository
4. Run notebooks in order:
   - notebooks/1_data_cleaning.ipynb
   - notebooks/2_eda.ipynb
   - notebooks/3_analysis.ipynb

## Project Structure
data/ - raw and cleaned datasets
notebooks/ - analysis notebooks (cleaning, EDA, analysis)
visualizations/ - generated charts
reports/ - executive summary and technical report
presentation/ - business presentation slides

## Methodology
1. **Data Cleaning** — Verified no missing values or duplicates
2. **Exploratory Data Analysis** — 5 visualizations analyzing 
   churn patterns across contract type, tenure, and charges
3. **Statistical Analysis** — Correlation analysis and t-test 
   to validate findings statistically

## Key Findings
1. Overall churn rate: 10.60%
2. Month-to-month contracts have 20.6% churn vs 4.3% (One-Year) 
   and 6.9% (Two-Year)
3. Churned customers average 6 months tenure vs 40 months for 
   retained customers (statistically significant, p < 0.001)
4. Higher monthly charges show mild association with churn

## Business Recommendations
1. Focus retention efforts on customers in their first 6-12 months
2. Incentivize customers to switch from month-to-month to 
   annual contracts
3. Monitor and engage high-charge customers with loyalty programs
4. Prioritize retention campaigns for new, month-to-month customers

## What I Learned
- End-to-end data analysis workflow (cleaning → EDA → analysis)
- Translating statistical findings into business recommendations
- Structuring a multi-notebook, professional data science project
- Statistical validation using hypothesis testing