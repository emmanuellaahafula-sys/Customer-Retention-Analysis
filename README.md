# Customer Retention Analysis

## Project Overview

This project analyses customer churn and retention patterns using the IBM Telco Customer Churn dataset.

The objective is to examine customer behaviour, contract types, tenure, payment methods, and internet services to identify patterns associated with customer churn and retention.

## Tools Used

- Microsoft Excel
- Microsoft SQL Server
- Microsoft Power BI
- DAX
- Power Query

## Project Workflow

### 1. Data Exploration — Excel

Excel was used for the initial inspection and exploration of the dataset.

The process involved reviewing the dataset structure, examining customer records, identifying missing values, and checking the data before proceeding to SQL Server.

### 2. Data Cleaning and Analysis — SQL Server

SQL Server was used to prepare the dataset for analysis.

The process included:

- Checking for missing values.
- Checking for duplicate customer records.
- Converting columns to appropriate data types.
- Handling blank values in the TotalCharges column.
- Creating a cleaned dataset.
- Analysing overall customer churn.
- Examining churn by contract type.
- Analysing churn across tenure groups.

### 3. Data Modelling and Visualisation — Power BI

Power BI was used to build an interactive dashboard presenting the key customer retention metrics and churn patterns.

DAX measures were created to calculate customer counts, churn rate, retention rate, and average customer tenure.

Power Query was used as part of the data preparation workflow.

## Dashboard Features

### Key Performance Indicators (KPIs)

- Total Customers
- Retained Customers
- Churned Customers
- Average Tenure
- Churn Rate
- Retention Rate

### Visualisations

- Churn Rate by Tenure
- Customer Count by Contract
- Customer Count by Payment Method
- Customer Distribution by Internet Service
- Churned vs. Retained Customers

## Interactive Features

The dashboard includes three slicers:

- Contract
- Payment Method
- Internet Service

These filters allow users to explore customer churn and retention patterns across different customer categories.

## Dataset

**Source:** IBM Telco Customer Churn dataset, available on Kaggle.

The dataset contains 7,043 customer records with information about customer demographics, subscribed services, account details, billing, tenure, and churn status.

## SQL Analysis Screenshot

The screenshot below presents the SQL analysis performed during the project.

![SQL Analysis Screenshot](REPLACE_WITH_EXACT_SQL_SCREENSHOT_FILENAME.png)

## Power BI Dashboard Screenshot

The dashboard provides an interactive overview of customer retention metrics and churn patterns.

![Customer Retention Analysis Dashboard](customer%20retention%20analysis.png)

## Key Findings

- The overall customer churn rate was approximately 26.54%.
- The customer retention rate was approximately 73.46%.
- The average customer tenure was approximately 32.37 months.
- Contract type and customer tenure were among the dimensions examined to understand churn patterns.

## Project Objective

To apply Excel, SQL Server, and Power BI to the data analysis process, from initial data exploration and cleaning to analytical querying, visualisation, and reporting.

The goal is to identify customer churn patterns and provide insights that can help businesses develop more effective customer retention strategies.

