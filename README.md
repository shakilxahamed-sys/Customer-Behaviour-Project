# Customer-Behaviour-Project

🛍️ Customer Behavior Analysis (CBR Project)
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The goal is to uncover insights into:

Customer spending patterns
Product preferences
Customer segmentation
Subscription behavior

These insights help support data-driven business decisions.

📊 Dataset Summary
Total Records: 3,900
Total Features: 18
Key Feature Groups:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Amount, Season, Size, Color
Shopping Behavior: Discounts, Promo Codes, Purchase Frequency, Ratings, Shipping Type
Data Quality:
Missing values found in Review Rating (37 entries)
Handled using median imputation per category
🧪 Exploratory Data Analysis (Python)

Performed using Pandas:

Key Steps:
Data loading and inspection (df.info(), df.describe())
Handling missing values
Column standardization (snake_case naming)
Feature engineering:
Age group categorization
Purchase frequency calculation
Data consistency checks:
Removed redundant promo_code_used column
Exported cleaned data to PostgreSQL
🗄️ SQL Analysis

Used PostgreSQL to answer business questions:

Key Insights:
Revenue comparison by gender
High-spending customers using discounts
Top 5 highest-rated products
Shipping type performance (Standard vs Express)
Subscriber vs non-subscriber behavior
Discount-dependent products
Customer segmentation:
New
Returning
Loyal
Top 3 products per category
Repeat purchase vs subscription correlation
Revenue contribution by age group
📈 Power BI Dashboard

An interactive dashboard was created to visualize:

Revenue trends
Customer segments
Product performance
Purchase behavior

Features:

Drill-down analysis
Dynamic filtering
Business-friendly visuals
💡 Business Recommendations

Based on analysis:

📢 Boost Subscriptions: Highlight exclusive benefits
🎯 Improve Loyalty Programs: Reward repeat customers
💰 Optimize Discounts: Balance profitability and sales
⭐ Promote Top Products: Focus on best-rated items
📊 Targeted Marketing: Focus on high-value segments
🛠️ Tech Stack
Python (Pandas) – Data cleaning & analysis
PostgreSQL – Querying & business insights
Power BI – Data visualization
🚀 How to Run
Clone the repository
Load dataset into Python
Perform EDA using Pandas
Export cleaned data to PostgreSQL
Run SQL queries
Open Power BI dashboard file
