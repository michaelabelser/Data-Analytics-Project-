# 🛒 Customer Shopping Behavior Analysis
*Google Data Analytics Capstone Project*

![Python](https://img.shields.io)
![SQL](https://img.shields.io)
![Power BI](https://img.shields.io)

## 📋 Project Overview
This project analyzes transactional data from **3,900 purchases** to uncover insights into spending patterns, customer segments, and product preferences. The goal was to provide data-driven recommendations for marketing and retention strategies.

### 🧾 Dataset Summary
- **Size:** 3,900 rows | 18 columns
- **Key Features:** Customer demographics, purchase details (amount, category, size), and shopping behavior (discounts, frequency, ratings).
- **Data Integrity:** Handled 37 null values in the `Review Rating` column.

---

## 🧠 Phase 1: Exploratory Data Analysis (Python)
Performed all data preparation and cleaning using **Pandas, NumPy, Matplotlib, and Seaborn**.

**Key Steps:**
*   **Missing Data:** Imputed null ratings using the median review score by product category.
*   **Standardization:** Renamed columns to `snake_case` for database compatibility.
*   **Feature Engineering:** 
    *   Binned ages into `age_group`.
    *   Calculated `purchase_frequency_days`.
*   **Integration:** Exported the cleaned DataFrame into **PostgreSQL** for deep-dive analysis.

---

## 💾 Phase 2: Business Analysis (SQL)
Used structured queries in PostgreSQL to answer critical business questions:

- **Revenue Analysis:** Compared performance across Gender and Subscription status.
- **Customer Segmentation:** Classified users as *New*, *Returning*, or *Loyal* based on history.
- **Discount Impact:** Identified products most reliant on promotions to drive sales.
- **Top Performers:** Ranked the Top 3 products per category by revenue and rating.

---

## 📊 Phase 3: Visualizations (Power BI)
Created an interactive dashboard to communicate findings to stakeholders.

<img width="1023" height="576" alt="Dashboard ScreenShot" src="https://github.com/user-attachments/assets/063b043e-334c-40fb-aaca-20a819c96def" />

**Key Dashboard Views:**
1. Total revenue by gender and subscription type.
2. Spending trends by age group and shipping preference.
3. Correlation between review ratings and discount usage.

---

## 💼 Business Recommendations
*   **Boost Subscriptions:** Highlight exclusive member benefits to grow recurring revenue.
*   **Loyalty Programs:** Incentivize "Returning" buyers to transition into "Loyal" status.
*   **Discount Optimization:** Rebalance discount policies to protect profit margins on high-rated products.
*   **Targeted Marketing:** Focus campaigns on high-value age groups identified in the analysis.

---
*Created as part of the Google Data Analytics Professional Certificate.*
