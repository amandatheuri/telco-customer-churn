Telco Customer Churn Analysis

📊 Project Overview

This project analyzes customer churn in a telecommunications dataset to identify high-risk customer segments and translate the findings into actionable retention strategies.

The analysis was completed as part of a Future Interns Data Analytics project.

Business Question

Who is most at risk of churning, and where should retention efforts be focused?

🎯 Objectives

Measure the overall customer churn rate.

Identify customer characteristics associated with higher churn.

Analyze the relationship between tenure and contract type.

Investigate monthly charges, internet service, and payment methods.

Identify high-risk customer segments.

Develop practical business recommendations for improving retention.

🗂️ Dataset

The analysis uses the Telco Customer Churn dataset containing 7,043 customer records and 21 variables.

Key fields include:

Customer demographics

Tenure

Contract type

Internet service

Payment method

Monthly charges

Total charges

Churn status

🛠️ Tools & Technologies

Python

Pandas — data loading, cleaning and analysis

Matplotlib — visualization

Seaborn — visualization

Jupyter Notebook

🔎 Data Preparation

The dataset was inspected for:

Number of rows and columns

Data types

Missing values

Duplicate records

Summary statistics

Data-quality issues

TotalCharges was originally stored as a text/object column and was converted to a numeric data type, with invalid/blank values coerced to missing values for appropriate handling.

📈 Key Findings

1. Overall churn

The overall customer churn rate is 26.54%.

Total customers: 7,043

Churned customers: 1,869

Retained customers: 5,174

2. Early-tenure customers are the biggest churn risk

Customers with 0–12 months of tenure have a 47.44% churn rate, compared with 9.51% among customers with 49–72 months of tenure.

3. Contract type strongly differentiates churn

Month-to-month: 42.71%

One year: 11.27%

Two year: 2.83%

4. The highest-risk segment is early-tenure, month-to-month customers

Customers with 0–12 months of tenure on month-to-month contracts have a 51.35% churn rate.

5. Fiber optic customers show elevated churn

Fiber optic: 41.89%

DSL: 18.96%

No internet service: 7.40%

6. Electronic-check customers show elevated churn

Electronic-check customers have a 45.29% churn rate, compared with 15.24% for automatic credit-card customers.

7. Monthly charges are higher among churned customers

Customer group

Average monthly charge

Median

Retained

$61.27

$64.43

Churned

$74.44

$79.65

This indicates an association between higher monthly charges and churn, although further analysis would be required to establish causation.

⚠️ Business Risks

High early-tenure churn may reduce customer lifetime value.

Elevated churn among fiber customers creates recurring-revenue exposure.

A large month-to-month customer base increases customer turnover risk.

💡 Opportunities

Strengthen first-year onboarding and retention.

Encourage suitable month-to-month customers to adopt longer contracts.

Investigate fiber pricing, reliability, technical support and customer experience.

📌 Recommendations

Launch an early-tenure retention program targeting customers during their first 12 months.

Encourage longer-term contracts through targeted incentives for suitable month-to-month customers.

Investigate fiber churn by reviewing pricing, service reliability, technical support and customer feedback.

Promote automatic payment methods while investigating the reasons behind the high churn among electronic-check customers.

Develop churn-risk segmentation to prioritize customers exhibiting multiple risk indicators.

📁 Project Structure

telco-customer-churn-analysis/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── telco_customer_churn_analysis.ipynb
│
├── presentation/
│   └── Telco_Customer_Churn_Business_Presentation.pptx
│
├── report/
│   ├── Business_Analytics_Report.pdf
│   └── Dataset_Inspection_Report.pdf
│
├── visuals/
│   └── charts/
│
└── README.md

Note: Large or restricted dataset files may be excluded from the repository. If the dataset cannot be redistributed, include instructions or a source link explaining how to obtain it instead.

📊 Deliverables

This project includes:

Business Understanding / Analytics Report

Python Jupyter Notebook

Dataset Inspection Report

Business Presentation

Data visualizations and analysis

🔗 Portfolio

This repository demonstrates an end-to-end business analytics workflow:

Business Understanding → Data Inspection → Data Cleaning → Exploratory Analysis → Business Insights → Recommendations

Author: Amanda TheuriFocus: Data Analytics | Business Intelligence | Python | Power BI | Excel
