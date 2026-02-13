🛍️ Customer Shopping Behavior Analysis
📊 Python | MySQL | Power BI
📌 Project Overview

This project analyzes customer shopping behavior using a transactional dataset of 3,900 purchases across multiple product categories. The goal is to uncover actionable insights related to customer spending patterns, product preferences, subscription behavior, discount impact, and customer segmentation.

The project follows an end-to-end data analytics workflow using:

Python for data cleaning & preprocessing

SQL for structured business analysis

Power BI for interactive dashboard visualization

This analysis helps businesses improve marketing strategies, customer engagement, and revenue optimization. 

Customer Shopping Behavior Anal…

🎯 Business Problem Statement

A retail company wants to better understand customer shopping behavior to improve sales, customer satisfaction, and loyalty. Management is interested in identifying how factors such as discounts, reviews, seasons, shipping preferences, and payment behavior influence customer decisions and repeat purchases.

🔍 Main Business Question:

"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?" 

Business Problem Document

📂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Customer Behavior: Discount Applied, Previous Purchases, Frequency of Purchases

Customer Feedback: Review Rating

Logistics: Shipping Type

Missing Values: 37 missing values in the review_rating column 

Customer Shopping Behavior Anal…

🛠️ Tools & Technologies Used
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning, transformation, feature engineering
MySQL	Data storage & SQL analysis (Business queries and insights extraction)
Power BI	Dashboard creation & visualization
GitHub	Project hosting and documentation

🧹 Data Cleaning & Preprocessing (Python Workflow)

The dataset was cleaned and transformed using Python to make it suitable for analysis and reporting.

✅ Steps Performed:

Imported dataset using Pandas

Performed initial inspection using .info() and .describe()

Checked for missing values and null handling

Imputed missing values in review_rating using median rating per category

Standardized column names into snake_case

Feature engineering:

Created age_group column by grouping age ranges

Created purchase_frequency_days from frequency values

Identified redundancy between discount_applied and promo_code_used

Dropped the promo_code_used column for simplification

Connected Python to PostgreSQL and exported cleaned dataset into database 

Customer Shopping Behavior Anal…

🗄️ SQL Analysis (MySQL)

After loading cleaned data into MySQL, multiple SQL queries were executed to solve real business questions and generate insights.

📌 Business Questions Answered:

Revenue by Gender – Compare total revenue between male and female customers

High-Spending Discount Users – Customers using discounts but spending above average

Top 5 Products by Rating – Products with the highest average ratings

Shipping Type Comparison – Standard vs Express spending comparison

Subscribers vs Non-Subscribers – Spending & revenue comparison

Discount-Dependent Products – Products with highest discounted purchases percentage

Customer Segmentation – New, Returning, Loyal customers based on purchase history

Top 3 Products per Category – Most purchased items in each category

Repeat Buyers & Subscriptions – Relationship between purchase count and subscription

Revenue by Age Group – Revenue contribution across age categories 

Customer Shopping Behavior Anal…

📊 Power BI Dashboard

A Power BI dashboard was created to visually represent key KPIs and trends in an interactive way.

📌 Dashboard Highlights:

Total Revenue & Total Purchases KPIs

Category-wise purchase distribution

Subscription vs Non-subscription performance

Gender and age-group revenue contribution

Discount impact analysis

Shipping preference trends

📌 Key Business Recommendations

Based on the analysis, the following business strategies were recommended:

✅ Boost Subscription Plans
Offer exclusive deals and benefits to convert more customers into subscribers.

✅ Launch Loyalty Programs
Reward repeat customers to increase retention and convert them into loyal buyers.

✅ Optimize Discount Strategy
Discounts should be controlled to ensure profitability while still increasing sales.

✅ Product Positioning Strategy
Promote top-rated and best-selling products in marketing campaigns.

✅ Targeted Marketing Campaigns
Focus marketing efforts on high-revenue customer groups and express-shipping users. 

Customer Shopping Behavior Anal…

📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behaviour.ipynb     # Python cleaning + preprocessing notebook
├── customer_shoping.sql                  # SQL queries for business analysis
├── Business Problem Document.pdf         # Business case statement
├── Customer Shopping Behavior Analysis.pdf # Analysis report
├── PowerBI_Dashboard.pbix                # Power BI dashboard file
└── README.md                             # Project documentation

🚀 How to Run This Project
1️⃣ Run Python Notebook

Open customer_shopping_behaviour.ipynb

Run all cells

Dataset will be cleaned and prepared for SQL analysis

2️⃣ Load Data into MySQL

Create a MySQL database

Upload cleaned dataset into a table

3️⃣ Execute SQL Queries

Open customer_shoping.sql

Run queries to generate insights

4️⃣ Open Power BI Dashboard

Open .pbix file in Power BI

Connect to database / dataset

Refresh visuals

📈 Project Outcomes

This project demonstrates the ability to:

Clean real-world data and handle missing values

Perform feature engineering and preprocessing

Write SQL queries to solve business problems

Segment customers based on purchasing behavior

Build interactive Power BI dashboards for business storytelling

📬 Author

Harsh Kumar
🎓 MBA (Finance + IT)
📊 Aspiring Data Analyst
