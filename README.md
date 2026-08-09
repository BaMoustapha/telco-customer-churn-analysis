# Telco Customer Churn Analysis

Business analytics case study conducted as part of the **AnalystLab Africa Data Analytics Internship Programme** (Week 1). Acting as a Junior Data Analyst, this project investigates customer churn for a fictional telecom client, ABC Communications Ltd, and translates the findings into actionable retention recommendations.

## Business Problem

ABC Communications Ltd is losing customers at a rate of 26.5%, well above the healthy 10-15% benchmark for the telecom industry. This project identifies which customer segments are most at risk, what drives their departure, and what the company can do about it.

## Dataset

[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (IBM Sample Dataset, via Kaggle) — 7,043 customers, 21 features covering demographics, account information, subscribed services, and churn status.

## Key Findings

| Driver | Finding |
|---|---|
| Contract type | Month-to-month customers churn at 42.7% vs 2.8% for two-year contracts, a 15x difference |
| Tenure | Churned customers have a median tenure of 10 months vs 38 months for retained customers |
| Internet service | Fiber optic customers churn at 41.9%, more than double DSL customers (19.0%) |
| Payment method | Electronic check users churn at 45.3%, nearly 3x automated payment methods |
| Demographics | Senior citizens churn at 41.7% vs 23.6% for non-seniors |


## Methodology

1. **Data Inspection**: Structure check, missing values, duplicates, data quality review
2. **Exploratory Analysis**: Descriptive statistics, cross-tabulations, correlation analysis
3. **Visualization**: Bar charts, pie charts, histograms, box plot, and correlation heatmap mapped to specific business questions
4. **Business Insights**: Key findings translated into risks and opportunities
5. **Recommendations**: Actionable, prioritized retention strategies for the client

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Google colab

## Recommendations Summary

1. Launch a contract upgrade incentive for month-to-month customers
2. Build a 90-day new customer retention program
3. Investigate fiber optic service quality and pricing perception
4. Incentivize migration to automatic payment methods
5. Create a dedicated senior citizen retention track
6. Deploy an early-warning churn risk score for the retention team

## Author

**Mouhamadou Moustapha BA**
Junior Data Analyst, AnalystLab Africa
[LinkedIn](https://linkedin.com/in/mouhamadoumoustaphaba) | [GitHub](https://github.com/BaMoustapha)

---
*This project was completed as part of the AnalystLab Africa Data Analytics Internship Programme.*
