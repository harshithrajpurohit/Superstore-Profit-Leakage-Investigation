# 🛒 Superstore Profit Leakage Investigation using Pandas

## Overview

This project analyzes the Superstore dataset to investigate whether aggressive discounting is reducing overall business profitability.

The analysis focuses on identifying profit leakage by examining discounts, high-sales loss-making orders, category performance, regional profitability, and suspicious business transactions using **Python** and **Pandas**.

---

## Business Problem

A regional sales manager observed that although overall sales were healthy, profits were not increasing.

The objective of this analysis was to answer questions such as:

- Are discounts reducing profitability?
- Which orders generate high sales but still incur losses?
- Which categories and sub-categories consistently underperform?
- Which regions experience the highest profit leakage?
- Which transactions should be reviewed by the pricing or sales teams?

---

## Dataset

**Source:** Superstore Dataset (Kaggle)

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook

---

## Analysis Performed

### Data Preparation
- Loaded the dataset
- Checked dataset dimensions
- Inspected columns and data types
- Converted Order Date and Ship Date into datetime format
- Checked missing values
- Checked duplicate records
- Calculated delivery time in days

### Feature Engineering
Created custom business flags including:

- High Discount Orders (>20%)
- Loss Orders
- High Sales Orders (Top 25%)
- High Sales but Loss-making Orders
- Discount Buckets

---

## Business Analysis

Performed analysis on:

- Sales summary
- Profit summary
- Discount behaviour
- High discount vs profit
- High discount vs loss percentage
- Category-wise profitability
- Sub-category performance
- Loss count by sub-category
- High discount concentration by sub-category
- Region-wise sales, profit and discount
- Region-wise loss percentage
- Segment-wise performance
- Discount bucket profitability
- High quantity with low profit orders
- Identification of problem orders

---

## Key Insights

- Orders with high discounts generated negative average profits.
- Higher discounts significantly increased the percentage of loss-making orders.
- Some high-revenue orders still resulted in losses.
- Certain sub-categories consistently showed weak profitability.
- Regional differences indicated inconsistent discount strategies.
- Multiple high-discount loss-making orders require pricing review.

---

## Business Recommendations

- Introduce discount limits to protect profit margins.
- Review pricing strategy for consistently loss-making products.
- Monitor high-sales orders that generate negative profits.
- Standardize discount policies across regions.
- Focus sales incentives on profitability rather than revenue.
- Regularly audit high-risk transactions.

---


## Learning Outcomes

This project helped strengthen my understanding of:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Business Analytics
- GroupBy Operations
- Business Problem Solving using Pandas

---

## Author

**Harshith Raj Purohit**

Interested in Data Analytics, Data Science, SQL, Python, Pandas, and Business Intelligence.
