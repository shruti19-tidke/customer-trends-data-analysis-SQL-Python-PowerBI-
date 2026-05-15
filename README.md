# customer-trends-data-analysis-SQL-Python-PowerBI-
🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases. The goal is to extract meaningful insights about:

Customer spending patterns
Product preferences
Subscription behavior
Customer segmentation

These insights help businesses make better strategic decisions.

📊 Dataset Summary
Total Rows: 3,900
Total Columns: 18
🔑 Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Amount, Season, Size, Color
Behavioral Data: Discount Applied, Promo Code Used, Purchase Frequency, Review Rating, Shipping Type

⚠️ Missing values were found in the Review Rating column.

🧹 Data Preprocessing
Loaded dataset using Pandas

Checked structure using df.info() and df.describe()

Handled missing values using median imputation (category-wise)

Standardized column names to snake_case

Removed redundant column: promo_code_used

⚙️ Feature Engineering
Created age_group from Age column
Derived purchase_frequency_days
Validated and cleaned inconsistent data

🗄️ Database Integration
Connected Python with PostgreSQL
Stored cleaned dataset for SQL-based analysis

📈 Data Analysis (SQL)
Key business insights extracted using SQL:
Revenue comparison by gender
High-spending customers using discounts
Top 5 highest-rated products
Purchase behavior by shipping type
Subscribers vs Non-subscribers analysis
Discount-dependent products
Customer segmentation:
New
Returning
Loyal
Top 3 products per category
Repeat buyers vs subscription trend
Revenue contribution by age group

📊 Dashboard

An interactive dashboard was created using Power BI to visualize:
Revenue trends
Customer segments
Product performance

Purchase behavior
💡 Business Recommendations
🚀 Promote subscription plans with exclusive benefits
🎯 Implement customer loyalty programs
💰 Optimize discount strategies
🛒 Highlight top-performing products
📢 Focus marketing on high-value customer groups

🛠️ Technologies Used
Python (Pandas)
SQL (PostgreSQL)
Power BI


📁 Project Structure
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
└── README.md
