# Data-Analytics-Project-
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal was to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions. I used Python, SQL and PowerBI to complete this project. 

Customer Shopping Behavior Analysis
📋 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The goal is to uncover insights into:

Spending patterns

Customer segments

Product preferences

Subscription behavior

These findings support data-driven marketing and retention strategies.

🧾 Dataset Summary

Rows: 3,900  Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

Missing Data:

37 null values in the Review Rating column

🧠 Exploratory Data Analysis (Python)

Performed all data preparation and EDA using Python (pandas, numpy, matplotlib, seaborn).

Steps:

Data Loading: Imported dataset with pandas.read_csv().

Initial Exploration: Used .info() and .describe() to review structure and summary stats.

Missing Data Handling: Imputed null ratings using the median review score by product category.

Column Standardization: Renamed columns to snake_case for readability.

Feature Engineering:

Created age_group by binning customer ages.

Calculated purchase_frequency_days from timestamps.

Dropped redundant promo_code_used column.

Data Consistency Check: Ensured logical relationships between discount and promo variables.

Database Integration: Uploaded cleaned DataFrame into PostgreSQL for SQL analysis.

💾 SQL Business Analysis (PostgreSQL)

Analyzed transactional trends and customer patterns using structured queries.

Key Business Queries:

Revenue by Gender: Compared total revenue between male and female customers.

High-Spending Discount Users: Found customers using discounts but exceeding average spend.

Top 5 Products by Rating: Ranked products with highest average review scores.

Shipping Type Comparison: Compared average purchase amounts between Standard and Express shipping.

Subscribers vs. Non-Subscribers: Analyzed revenue and average spend across segments.

Discount-Dependent Products: Identified top 5 products most reliant on discounts.

Customer Segmentation: Classified customers as New, Returning, or Loyal based on purchase history.

Top 3 Products per Category: Listed best-selling items by category.

Repeat Buyers & Subscriptions: Measured correlation between frequent purchases and subscription likelihood.

Revenue by Age Group: Quantified total revenue per age group.

📊 Power BI Dashboard

Created an interactive Power BI dashboard to visualize:

Total revenue by gender and subscription type

Top products and categories by revenue and rating

Spending trends by age group and shipping preference

Discount usage and impact on sales

(Insert dashboard screenshot or link here)

💼 Business Recommendations

Based on the analysis:

Boost Subscriptions: Highlight exclusive member benefits to grow recurring revenue.

Customer Loyalty Programs: Incentivize repeat buyers to transition into “Loyal” customers.

Review Discount Policy: Rebalance discounts to protect profit margins.

Product Positioning: Promote top-rated and high-selling products in campaigns.

Targeted Marketing: Focus on high-value age groups and express-shipping customers.
