# Customer Retention & Churn Analysis

## Project Overview

Customer retention is important for any business that wants to grow and maintain a good relationship with its customers. In this project, I used Power BI to analyse customer churn and understand the patterns behind customers leaving a subscription service.

The main goal was to explore customer behaviour, identify customer groups with higher churn rates, and find areas where the business could improve retention.

This project was completed as part of the **Future Interns – Data Science & Analytics Internship, Task 2**.

## Objectives

Through this project, I aimed to:

- Understand the overall customer churn and retention rate.
- Explore churn patterns across different contract types.
- Compare customer churn based on payment methods and internet services.
- Study how customer tenure relates to retention.
- Compare the monthly and total charges of customers.
- Create an interactive Power BI dashboard to present the analysis clearly.

## Dataset

**Dataset:** Telco Customer Churn

**Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

I used the Telco Customer Churn dataset, which contains information about customers, their subscription plans, services, payment methods, tenure, charges, and churn status.

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- CSV Dataset

## Data Preparation

Before starting the analysis, I imported the dataset into Power BI and prepared it for use.

The data preparation steps included:

- Checking and correcting column data types.
- Cleaning the `TotalCharges` column.
- Removing rows with blank total charges.
- Organising the data for analysis.
- Creating measures to calculate customer and churn metrics.
- Grouping customers based on their tenure.

## Dashboard Pages

### Page 1 – Customer Churn & Retention Dashboard

The first page gives an overall view of customer churn and retention. It includes:

- Total Customers
- Churned Customers
- Retained Customers
- Overall Churn Rate
- Churn by Contract
- Churn by Payment Method
- Churn by Internet Service
- Churn by Tenure Group
- Churn by Gender
- Churn by Senior Citizen Status

### Page 2 – Customer Retention Analysis

The second page focuses more on customer behaviour and how long customers stay with the service. It includes:

- Average Customer Tenure
- Average Monthly Charges
- Average Total Charges
- Average Tenure by Contract Type
- Comparisons between customers who churned and those who stayed

## Key Findings

After analysing the dataset, I observed the following patterns:

- The overall churn rate in the cleaned dataset is approximately **26.6%**.
- Customers with month-to-month contracts show a higher churn rate than customers with longer contracts.
- Customers in shorter tenure groups are more likely to churn.
- Fiber optic customers have a higher churn rate compared with other internet service groups.
- Customers using electronic check payments show a higher churn rate among the payment methods.
- Customers who leave the service generally have a lower average tenure than customers who stay.

These findings helped me understand how different customer groups behave. They show patterns in the data, but they do not prove that a particular factor directly causes churn.

## Business Recommendations

Based on the patterns I observed, a subscription-based business could consider the following actions:

- Improve the experience of customers using month-to-month contracts.
- Provide better onboarding and support for new customers.
- Understand the concerns of fiber optic customers and improve their service experience.
- Make payment options more convenient for customers.
- Collect customer feedback to better understand why customers leave.
- Focus on retention strategies for customer groups with higher churn rates.

## Project Files

The repository includes:

- Power BI dashboard file (`.pbix`)
- Dashboard PDF
- Dashboard screenshots
- Project documentation

## How to View the Dashboard

1. Download the `.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Explore the dashboard pages and use the slicers to view different customer groups.

## Project Details

**Internship:** Future Interns – Data Science & Analytics

**Task:** Task 2 – Customer Retention & Churn Analysis

**Domain:** Data Science and Business Analytics
