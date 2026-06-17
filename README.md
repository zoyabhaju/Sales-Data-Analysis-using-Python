# 📊 Sales Data Analysis using Python

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a sales dataset containing over 186,000 transactions to uncover customer purchasing patterns, product performance, and revenue trends. Using Python, the data was cleaned, transformed, and analyzed to answer real-world business questions and generate actionable business insights.

The project explores sales performance across different products, cities, and time periods while identifying opportunities to optimize advertisement timing and product bundling strategies.


## 📂 Dataset

The dataset consists of sales transaction records collected throughout 2019. It was created by concatenating 12 separate monthly CSV files (January–December 2019) into a single dataset containing over 186,000 transactions.

Each row represents an individual product purchased within an order and includes customer purchase information such as product details, order date, quantity, price, and purchase location.

During preprocessing, repeated header rows introduced during the concatenation process were identified and removed before further analysis.

- Order ID
- Product
- Quantity Ordered
- Price Each
- Order Date
- Purchase Address

Dataset Size: ~186,000+ records spanning January–December 2019.

## 🛠️ Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Collection & Consolidation

Combined 12 monthly sales datasets from January to December 2019 into a single dataset.

### 2. Data Cleaning

- Removed invalid and repeated header rows
- Handled missing values
- Corrected numerical and datetime data types

### 3. Feature Engineering

Created additional features to support analysis:

- Month
- Month Name
- Hour
- City
- Sales

### 4. Exploratory Data Analysis (EDA)

Performed analyses to uncover patterns related to:

- Monthly sales performance
- City-wise revenue distribution
- Customer purchasing hours
- Product performance

### 5. Market Basket Analysis

Identified products that are frequently purchased together to uncover cross-selling opportunities.

### 6. Data Visualization

The repository includes visualizations for:

- Monthly Sales Analysis
- Sales by City
- Customer Purchasing Hours
- Products Sold Together
- Product Sales vs Average Price

## 📈 Key Insights

- Identified the highest-performing sales months throughout 2019.
- Determined peak customer purchasing hours to optimize advertisement timing.
- Identified top-performing cities by revenue.
- Discovered products frequently purchased together.
- Analyzed the relationship between product pricing and sales volume.

## 🚀 Skills Demonstrated

Data Cleaning, Data Transformation, Feature Engineering, Exploratory Data Analysis (EDA), Data Visualization, Time-based Analysis, Market Basket Analysis, Business Insight Generation
