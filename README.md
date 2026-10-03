# Customer Shopping Behavior Analysis

📊 Project Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI to identify purchasing patterns, customer segments, product/category performance, and factors related to customer spending.

The project follows an end-to-end data analytics workflow, from data cleaning and exploratory analysis to SQL-based business analysis and interactive Power BI visualization.

 🎯 Business Objective

The main objective is to transform raw retail customer data into meaningful, decision-ready insights that help understand:

- Customer purchasing behavior
- Product and category performance
- Spending patterns
- Customer segments
- Subscription and promotional behavior
- Payment and shipping preferences
- Purchase frequency
- Customer review patterns

📁 Dataset

The dataset contains 3,900 customer purchase records and 18 columns.

Key fields include:

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

 Data Quality

- 3,900 rows
- 18 columns
- 37 missing values in Review Rating
- No duplicate rows identified

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL / PostgreSQL
- Power BI
- DAX
- GitHub

🔄 Project Workflow

Raw Dataset  
↓  
Data Loading & Profiling  
↓  
Data Cleaning  
↓  
Missing-Value Treatment  
↓  
Feature Engineering  
↓  
Exploratory Data Analysis  
↓  
SQL Business Analysis  
↓  
Power BI Dashboard  
↓  
Business Insights  
↓  
Documentation & Presentation

📈 Power BI Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior.

Dashboard Preview
![Uploading Screenshot 2026-10-03 153654.png…]()



Dashboard Includes

- Number of Customers
- Average Purchase Amount
- Average Review Rating
- Customer distribution by Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Gender filter
- Subscription Status filter
- Category filter
- Shipping Type filter

 🔍 Key Analysis Areas

# Customer Analysis

Analyze customer distribution based on gender, age groups, subscription status, and purchasing behavior.

# Product & Category Analysis

Compare sales and revenue across product categories to understand category-level performance.

# Spending Analysis

Study purchase amounts and average spending patterns across different customer groups.

# Promotion & Subscription Analysis

Explore relationships between subscription status, discounts, promo-code usage, and purchasing behavior.

# Purchase Behavior

Analyze payment methods, shipping preferences, purchase frequency, previous purchases, and review ratings.

# 🧹 Data Cleaning

The Python workflow includes:

1. Loading the raw CSV dataset
2. Checking rows, columns, and data types
3. Identifying missing values
4. Checking duplicate records
5. Validating categorical and numerical fields
6. Handling missing Review Rating values using a justified approach
7. Creating analysis-ready features
8. Exporting the cleaned dataset for SQL and Power BI analysis

The missing-value treatment is selected based on the characteristics of the actual data rather than blindly applying a predefined method.

## 🗃️ SQL Analysis

SQL is used to answer business questions using:

- Aggregations
- GROUP BY
- CASE statements
- Subqueries
- CTEs
- Window functions
- Ranking
- Category-level analysis
- Customer-level analysis

## 💡 Business Insights

The analysis focuses on identifying measurable patterns in:

- Customer spending
- Category performance
- Age-group behavior
- Subscription participation
- Promotion usage
- Purchase frequency
- Shipping preferences
- Payment methods
- Review ratings

The insights are derived from the dataset and are not intended to establish causal relationships.

## 📂 Project Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── customer_shopping_behavior_cleaned.csv
│
├── python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_shopping_behavior_analysis.sql
│
├── powerbi/
│   └── customer_shopping_behavior_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis_Report.pdf
│
├── presentation/
│   └── Customer_Shopping_Behavior_Analysis.pptx
│
├── business_problem/
│   └── Customer_Shopping_Behavior_Problem_Statement.pdf
│
└── README.md
