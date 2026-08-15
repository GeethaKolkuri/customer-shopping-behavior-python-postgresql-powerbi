# 🛍️ Customer Shopping Behavior Analysis – Python, PostgreSQL & Power BI

## 📊 Project Overview

This is an end-to-end customer shopping behavior analysis project using **Python, PostgreSQL, and Power BI**.

The project focuses on understanding customer purchasing patterns, subscription behavior, discounts, product performance, shipping preferences, ratings, and customer segments.

Python is used for data cleaning and feature engineering, PostgreSQL is used for business-focused SQL analysis, and Power BI is used to create an interactive customer behavior dashboard.

## 🎯 Objectives

- Clean and prepare customer shopping data using Python.
- Handle missing review ratings.
- Standardize column names.
- Create customer age groups.
- Convert purchase frequency into numerical day values.
- Remove redundant fields.
- Analyze customer revenue and purchasing behavior.
- Compare subscribed and non-subscribed customers.
- Analyze discounts and shipping types.
- Identify top-rated and most-purchased products.
- Segment customers based on previous purchases.
- Build an interactive Power BI dashboard.

## 🗂️ Dataset

The project uses:

`customer_shopping_behavior.csv`

The original dataset contains **3,900 customer records and 18 columns**.

The dataset includes:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- PostgreSQL
- SQL
- Power BI
- Data Cleaning
- Data Transformation
- Data Visualization

## 🔄 Python Analysis

The Python notebook:

- Loads the customer shopping dataset.
- Inspects the data structure and summary statistics.
- Checks missing values.
- Fills missing `Review Rating` values using the median rating within each category.
- Converts column names to lowercase.
- Replaces spaces in column names with underscores.
- Renames `purchase_amount_(usd)` to `purchase_amount`.
- Creates four age groups:
  - Young Adult
  - Adult
  - Middle-aged
  - Senior
- Converts purchase frequencies such as Weekly, Monthly, Quarterly, and Annually into numerical day values.
- Checks the relationship between discount and promo-code fields.
- Removes the redundant `promo_code_used` column.

## 🐘 PostgreSQL Analysis

The PostgreSQL analysis is stored in:

`3 tools PBI PYTHON PGSQL customers.sql`

The SQL analysis includes:

- Revenue by gender.
- Customers who used discounts but spent above the average purchase amount.
- Top 5 products by average review rating.
- Average purchase amount by shipping type.
- Comparison of subscribed and non-subscribed customers.
- Top 5 products with the highest discount rate.
- Customer segmentation into New, Returning, and Loyal customers.
- Top 3 products within each category.
- Relationship between repeat purchases and subscription status.
- Revenue contribution by age group.

## 📈 Power BI Dashboard

The Power BI project is stored in:

`3 tools proj_1 PBI,pgsql,python.pbix`

The dashboard provides an interactive view of customer behavior.

### Key KPIs

- **Number of Customers:** 3.9K
- **Average Purchase Amount:** $59.8
- **Average Review Rating:** 3.75

### Dashboard Analysis

The dashboard includes:

- Customer subscription status
- Gender filters
- Category filters
- Shipping type filters
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group

## 💡 Key Insights

- The dataset contains **3,900 customers**.
- The average purchase amount is approximately **$59.76**.
- The average review rating is approximately **3.75**.
- **73%** of customers are non-subscribers, while **27%** are subscribers.
- Clothing generates the highest revenue among the analyzed categories.
- Clothing also has the highest number of sales.
- Young Adult customers contribute the highest revenue among the age groups.
- Customer purchasing behavior can be further analyzed through subscription status, discounts, shipping type, and previous purchases.

## 🚀 Skills Demonstrated

- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- SQL Aggregation
- Window Functions
- Customer Segmentation
- Revenue Analysis
- Sales Analysis
- Data Visualization
- Dashboard Development
- Business Intelligence

## 📁 Repository Structure

```text
customer-shopping-behavior-python-postgresql-powerbi/
│
├── README.md
│
├── customer_shopping_behavior.csv
│
├── 1st py,PBI,SQL.ipynb
│
├── 3 tools PBI PYTHON PGSQL customers.sql
│
├── 3 tools proj_1 PBI,pgsql,python.pbix
│
└── 3 tools dasboard snip pbi,pgsql,python.jpg
```
📌 Conclusion

This project demonstrates a complete customer shopping behavior analysis workflow using Python, PostgreSQL, and Power BI.

Python is used for data cleaning and feature engineering, PostgreSQL is used to answer business questions through SQL, and Power BI is used to present the results through an interactive dashboard.

Overall, the project demonstrates practical skills in Python, Pandas, PostgreSQL, SQL, Power BI, data cleaning, feature engineering, customer segmentation, sales analysis, data visualization, and business intelligence.
