# Project 2 — Exploratory Data Analysis

## 📊 Project Overview

This project was completed as part of Data Analytics project.

The objective of Project 2 was to perform Exploratory Data Analysis (EDA) on a cleaned e-commerce order dataset and uncover meaningful patterns, trends, distributions, relationships, and potential outliers.

## 🎯 Project Objectives

- Calculate basic descriptive statistics
- Analyze order and sales distributions
- Identify sales trends
- Analyze product and order behavior
- Identify potential outliers
- Analyze relationships between numerical variables
- Summarize key analytical findings

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Microsoft Excel

## 📁 Dataset

The cleaned dataset contains:

- **1,200 orders**
- **1,189 unique customers**
- **7 products**
- **14 original columns**

The dataset contains information related to orders, products, quantity, unit price, payment methods, order status, referral sources, coupon codes, and total order price.

## 📈 Key Analysis Performed

### 1. Basic Statistics

Calculated:

- Count
- Mean
- Median
- Minimum
- Maximum
- Standard deviation

### 2. Order Status Analysis

Analyzed the distribution of orders across different order statuses.

### 3. Sales Distribution

Analyzed the distribution of TotalPrice and identified the concentration of orders in lower price ranges.

### 4. Quantity Analysis

Analyzed order quantities ranging from 1 to 5 units.

### 5. Sales Trend Analysis

Year-wise sales analysis showed a decline in total sales from 2023 to 2025.

### 6. Referral Source Analysis

Instagram generated the highest number of orders among the analyzed referral sources.

### 7. Coupon Code Analysis

FREESHIP was associated with the highest number of orders among the coupon categories.

### 8. Correlation Analysis

Important relationships were identified between numerical variables.

- UnitPrice vs TotalPrice: **0.72**
- Quantity vs TotalPrice: **0.62**
- Quantity vs ItemsInCart: **0.65**

### 9. Outlier Analysis

The IQR method identified **8 potential high-value outliers** in TotalPrice.

The calculated upper bound was approximately **₹3,330.41**.

### 10. Highest Value Orders

The highest-value order had a TotalPrice of **₹3,456.40**.

## 📌 Key Findings

- Total sales were **₹1,264,762.00**.
- Average order value was **₹1,053.97**.
- Median order value was **₹823.62**.
- Maximum order value was **₹3,456.40**.
- Minimum order value was **₹11.39**.
- UnitPrice showed a strong positive relationship with TotalPrice.
- Quantity also showed a positive relationship with TotalPrice.
- Sales showed a declining yearly trend from 2023 to 2025.
- Eight potential high-value outliers were identified.

## 💡 Business Insights

The analysis indicates that unit price and quantity are important factors associated with total order value. The decline in yearly sales suggests that sales performance should be monitored closely. Referral source analysis indicates that Instagram generated the highest order volume among the analyzed sources.

The identified high-value orders can also be examined separately to understand the factors contributing to larger transactions.

## 📂 Project Files

- `DecodeLabs_Project2_EDA_Ayush.ipynb` — Complete Google Colab EDA notebook
- `Project1_Cleaned.xlsx` — Cleaned dataset used for the analysis

## 👨‍💻 Project

**Data Analytics Internship — Project 2**

**Project:** Exploratory Data Analysis (EDA)
