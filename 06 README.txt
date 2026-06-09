# Superstore Sales Performance Analysis
## Project Overview

This project analyzes the Superstore retail dataset containing 9,994 transactions from 2014–2017. The objective was to identify sales trends, profitability drivers, customer performance, regional performance, and the impact of discounts on business profitability.
The project follows a complete data analytics workflow:
- Data Cleaning and Validation using Excel & Power Query
- Data Analysis using PostgreSQL
- Exploratory Data Analysis (EDA) using Python
- Interactive Dashboard Development using Power BI
- Business Insights and Recommendations

## Business Problem
Retail businesses often struggle to identify:
- High-performing products and categories
- Loss-making products
- Profitable customers
- Regional performance differences
- The impact of discounts on profitability
This project aims to transform raw transaction data into actionable business insights.

## Tools & Technologies
| Tool | Purpose |
|--------|---------|
| Excel | Data Cleaning & Validation |
| Power Query | Data Transformation |
| PostgreSQL | Data Analysis & Querying |
| Python | Exploratory Data Analysis (EDA) |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Power BI | Interactive Dashboard Development |
| GitHub | Project Documentation & Version Control |

## Dataset Information
**Dataset:** Superstore Sales Dataset
The dataset contains retail sales transactions from 2014 to 2017 and includes:
- Orders
- Customers
- Products
- Categories
- Regions
- Sales
- Profit
- Discounts
- Shipping Information

### Dataset Summary
| Metric | Value |
|----------|---------|
| Total Records | 9,994 |
| Time Period | 2014 – 2017 |
| Categories | 3 |
| Sub-Categories | 17 |
| Regions | 4 |
| Customers | 793 |
| Products | 1,849 |

## Project Workflow
### 1. Data Cleaning (Excel & Power Query)
- Removed inconsistencies and formatting issues
- Validated date fields
- Checked for missing values
- Standardized column formats

### 2. SQL Analysis (PostgreSQL)
Performed business analysis using SQL queries:
- Sales Performance Analysis
- Profit Analysis
- Regional Analysis
- Customer Analysis
- Product Performance Analysis

### 3. Python EDA
Performed exploratory data analysis to identify:
- Sales Trends
- Profit Trends
- Regional Performance
- Category Performance
- Customer Behavior
- Discount Impact

### 4. Power BI Dashboard
Developed an interactive dashboard featuring:
- KPI Tracking
- Sales Trends
- Profitability Analysis
- Regional Performance
- Customer Analysis
- Discount Impact Analysis

## Key Business Questions
The analysis focused on answering the following questions:
1. Which product categories generate the highest sales?
2. Which sub-categories generate the highest profit?
3. Which products are loss-making?
4. Which regions contribute the most revenue?
5. Who are the most profitable customers?
6. How do discounts impact profitability?
7. What are the monthly sales trends?
8. Which business areas require improvement?

## Exploratory Data Analysis (Python)
The dataset was analyzed using Pandas, Matplotlib, and Seaborn to uncover patterns in sales, profitability, customer behavior, and regional performance.

### Key Findings
- Sales showed a consistent upward trend from 2014 to 2017.
- Technology was the highest-performing category in terms of revenue.
- Copiers generated the highest profit among all sub-categories.
- Tables and Bookcases were identified as loss-making sub-categories.
- The West region generated the highest sales and profit.
- High discount levels were frequently associated with lower profitability.
- A small group of customers contributed a significant share of total profit.

### Visualizations Created
1. Monthly Sales Trend
2. Monthly Profit Trend
3. Sales by Category
4. Profit by Sub-Category
5. Regional Performance Analysis
6. Discount vs Profit Analysis

## Power BI Dashboard
An interactive dashboard was developed to monitor key business metrics and support decision-making.

### Dashboard Features

#### KPI Cards
- Total Sales
- Total Profit
- Profit Margin %
- Total Orders
- Average Discount %

#### Visualizations
- Sales Trend Over Time
- Profit by Region
- Profitability by Sub-Category
- Top 5 Customers by Profit
- Impact of Discounts on Profitability
- Sales by Category Distribution

#### Interactive Filters
- Year
- Region
- Category

## Key Business Insights

### Revenue Drivers
- Technology generated the highest sales contribution.
- Office Supplies and Furniture contributed significant revenue but lower profitability.

### Profitability Analysis
- Copiers, Phones, and Accessories were the most profitable sub-categories.
- Tables and Bookcases generated losses and require attention.

### Regional Analysis
- The West region achieved the highest overall sales and profit.
- The South region showed comparatively lower performance.

### Customer Analysis
- A small number of customers contributed disproportionately to total profit.
- High-value customers should be targeted for retention strategies.

### Discount Analysis
- Excessive discounts negatively impacted profitability.
- Orders with higher discount percentages frequently resulted in reduced or negative profit.

## Business Recommendations
Based on the analysis, the following recommendations were identified:
1. Increase focus on high-profit products such as Copiers and Phones.
2. Review pricing and discount strategies for Tables and Bookcases.
3. Optimize discount policies to protect profit margins.
4. Expand successful sales strategies used in the West region.
5. Develop retention programs for high-profit customers.
6. Monitor loss-making products and adjust inventory planning accordingly.
