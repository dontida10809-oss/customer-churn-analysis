# Customer Churn Analysis Project (Data Analyst)

## Project Overview

This project analyzes **customer churn behavior** using transactional sales data.
The main goal is to understand **when customers stop purchasing** and whether churn is related to changes in sales performance.

Churn is defined as:

> **A customer who does not make another purchase within 60 days**

This project is designed as a **Data Analyst portfolio project** suitable for internship applications.

---

## Business Problem

Businesses often experience customers who purchase once and never return.
However, it is not always clear:

* When a customer should be considered "lost"
* Whether declining sales are directly caused by customer churn

Understanding churn timing helps businesses:

* Plan re-engagement campaigns
* Improve customer retention strategies
* Reduce revenue loss

---

## Analytical Approach

1. **Data Preparation**

   * Loaded transactional sales data using Python (pandas)
   * Converted date columns to datetime format

2. **Churn Definition**

   * Calculated the number of days between purchases per customer
   * Labeled customers as `Churn = True` if inactivity exceeded 60 days

3. **Monthly Aggregation**

   * Aggregated total sales per month
   * Counted churned customers per month

4. **Visualization**

   * Compared monthly total sales with monthly churn counts

---

## Key Results

| Month   | Total Sales | Churn Customers |
| ------- | ----------- | --------------- |
| 2024-01 | 320         | 1               |
| 2024-02 | 180         | 0               |
| 2024-03 | 140         | 0               |

### Insights

* Although total sales declined from January to March, customer churn occurred **only in January**.
* This indicates that **short-term sales decline does not necessarily cause churn**.
* Customers who continued purchasing after January showed stronger retention behavior.

---

## Business Interpretation

* January may include **one-time or promotion-driven customers**.
* Customers retained in later months likely have **higher loyalty**.
* Businesses should focus on:

  * Re-engaging customers shortly after their first purchase
  * Improving post-purchase experience instead of relying only on promotions

---

## 🛠 Tools & Skills Used

* Python
* pandas
* matplotlib
* Data Cleaning & Transformation
* Exploratory Data Analysis (EDA)
* Business Insight Communication

---

## Why This Project Matters

This project demonstrates:

* Analytical thinking
* Ability to translate data into business insights
* Understanding of customer behavior metrics

It reflects the **core responsibilities of a Data Analyst role**.

---

## Future Improvements

* Segment churn by product type
* Analyze customer lifetime value (CLV)
* Build a dashboard using Power BI or Tableau

---

## Author

**Dolthida**
Aspiring Data Analyst | Internship Portfolio Project
