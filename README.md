# Sales Data Analysis using Python

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a sales dataset containing over 186,000 transactions to uncover customer purchasing patterns, product performance, and revenue trends using Python. The objective was to answer real-world business questions and derive actionable insights from transactional data.

The analysis identified monthly sales trends, peak customer purchasing hours, top-performing cities, and best-selling products. Market basket analysis was also performed to determine products that are frequently purchased together, providing insights for cross-selling and promotional strategies.

## Dataset

The dataset consists of sales transaction records collected throughout the year 2019. It was created by concatenating 12 separate monthly CSV files (January to December) into a single dataset containing over 186,000 transactions.

Each record represents an individual product purchased within an order and includes information such as Order ID, Product Name, Quantity Ordered, Price Each, Order Date, and Purchase Address.

During preprocessing, repeated header rows introduced during the concatenation process were identified and removed before performing further analysis.

Key columns:

Order ID
Product
Quantity Ordered
Price Each
Order Date
Purchase Address

Dataset Size: ~186,000+ records spanning January–December 2019.

## Business Questions Answered
Which month generated the highest sales?
Which cities contributed the most revenue?
What time should advertisements be displayed to maximize customer purchases?
Which products are most frequently purchased together?
Which products sold the most and how does pricing influence sales volume?

## Project Workflow
1. Data Collection & Consolidation: Combined 12 monthly sales datasets from January to December 2019 into a single dataset containing over 186,000 transactions.
2. Data Cleaning: Removed invalid and duplicate header rows, handled missing values, and corrected data types for numerical and datetime columns.
3. Feature Engineering: Created new features such as Month, Month Name, Hour, City, and Sales to support deeper analysis.
4. Exploratory Data Analysis (EDA): Analyzed monthly sales trends, city-wise performance, customer purchasing hours, and product performance.
5. Market Basket Analysis: Identified products frequently purchased together to uncover cross-selling opportunities.
6. Data Visualization: Built charts using Matplotlib to communicate key business insights and support data-driven decision-making.
7. Business Insights: Generated recommendations on advertisement timing, product bundling strategies, and factors influencing product sales.

## Tools & Technologies

Python, Pandas, NumPy, Matplotlib

## Skills Demonstrated

Data Cleaning, Data Transformation, Feature Engineering, Exploratory Data Analysis (EDA), Data Visualization, Time-based Analysis, Market Basket Analysis, and Business Insight Generation.
