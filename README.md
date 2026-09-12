# Customer Churn Analysis

## Overview

This project analyzes customer churn using **Python, statistical analysis, and Power BI**. The goal is to identify churn patterns, understand high-risk customer groups, and provide insights that can support customer retention and revenue protection.

## Dataset

The project uses a **Telco Customer Churn** dataset containing customer information such as:

* Customer demographics
* Tenure
* Contract type
* Payment method
* Internet service
* Tech support
* Monthly charges
* Total charges
* Churn status

## Analysis Performed

### Data Preparation

* Inspected the dataset structure and data types
* Checked missing and duplicate values
* Converted `TotalCharges` to numeric format
* Handled missing values
* Standardized `SeniorCitizen` values

### Exploratory Analysis

The analysis examines churn based on:

* Contract type
* Tenure groups
* Monthly charges
* Payment method
* Internet service
* Tech support

### Statistical Analysis

Two statistical tests were performed:

* **Chi-Square Test** — Contract Type vs. Churn
* **Independent Samples T-Test** — Monthly Charges vs. Churn

These tests were used to determine whether observed differences and relationships were statistically significant.

### Customer Segmentation

Customers were grouped into four rule-based segments:

* **New**
* **High-Risk**
* **High-Value**
* **Loyal**

### Revenue at Risk

Monthly revenue at risk was calculated using the monthly charges of churned customers to understand the potential recurring revenue impact of churn.

## Power BI Dashboard

A Power BI dashboard was created to provide an interactive view of:

* Overall churn
* Customer segments
* Contract-based churn
* Tenure-based churn
* Payment methods
* Internet services
* Tech support
* Revenue-related insights

## Key Findings

The analysis identified **month-to-month customers, newer customers, electronic-check users, and high-value customers** as important groups for further retention analysis.

The overall customer churn rate was approximately **26.53%**, highlighting the importance of proactive customer retention strategies.

## Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SciPy**
* **Jupyter Notebook**
* **Power BI**

## Conclusion

This project demonstrates how customer data can be cleaned, analyzed, statistically tested, and visualized to identify churn patterns and support data-driven retention decisions.
