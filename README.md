🛒 Customer Shopping Behavior Analysis:

📌 Project Overview:
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The objective is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

📂 Dataset Summary:
Total Records: 3,900
Total Columns: 18

Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior:
Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type
Data Quality:
Missing Values: 37 missing entries in the review_rating column

🧹 Exploratory Data Analysis (Python):
I performed data cleaning, preparation, and feature engineering using Python (Pandas).
Steps Performed:

Data Loading: Imported the dataset using Pandas
Initial Exploration:
Used df.info() to understand data structure
Used df.describe() for summary statistics

Missing Value Handling:
Imputed missing review_rating values using the median rating per product category

Column Standardization:
Converted column names to snake_case for consistency and readability

Feature Engineering:
Created age_group by binning customer ages
Created purchase_frequency_days from purchase behavior data

Data Consistency Check:
Identified redundancy between discount_applied and promo_code_used
Dropped promo_code_used column

Database Integration:
Connected Python to Microsoft SQL Server
Loaded the cleaned dataset into SQL for advanced analysis

🗄️ Data Analysis Using SQL (Business Transactions):

I used Microsoft SQL Server to answer key business questions:
Revenue by Gender – Compared total revenue from male vs. female customers.

High-Spending Discount Users – Identified customers who used discounts but still spent above the average purchase amount.

Top 5 Products by Rating – Products with the highest average review ratings.

Shipping Type Comparison – Average purchase amount for Standard vs. Express shipping.

Subscribers vs. Non-Subscribers – Compared total revenue and average spend.

Discount-Dependent Products – Top 5 products with the highest percentage of discounted purchases.

Customer Segmentation – Classified customers as New, Returning, or Loyal.

Top 3 Products per Category – Most purchased products in each category.

Repeat Buyers & Subscriptions – Analyzed if customers with more than 5 purchases are more likely to subscribe.

Revenue by Age Group – Total revenue contribution by each age group.

📊 Power BI Dashboard:

I built an interactive Power BI dashboard to visualize insights, including:
Revenue trends by customer demographics.
Product performance by category and rating.
Subscription and shipping behavior analysis.

💡 Business Recommendations:

Based on the analysis, I recommend:
Boost Subscriptions: Promote exclusive benefits to increase subscriber adoption.
Customer Loyalty Programs: Reward repeat buyers to move them into the Loyal segment.
Review Discount Strategy: Balance discounts to maximize revenue without hurting margins.
Product Positioning: Highlight top-rated and best-selling products in marketing campaigns.
Targeted Marketing: Focus on high-revenue age groups and express-shipping customers.

🛠️ Tools & Technologies:
Python: Pandas, NumPy
SQL: Microsoft SQL Server
Visualization: Power BI

📈 Key Takeaway:
This project demonstrates my ability to clean data, perform exploratory and SQL-based analysis, and translate insights into actionable business recommendations using industry-standard tools.
