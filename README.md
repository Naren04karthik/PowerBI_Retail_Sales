# Retail Store Sales Performance & Inventory Optimization

## Project Overview

This project focuses on analyzing retail sales and inventory data for a national retail chain operating across multiple store locations. The objective of the project is to identify sales trends, optimize inventory management, evaluate profitability, and generate actionable business insights using Power BI.

The dashboard solution enables management teams to monitor store performance, identify stockout risks, analyze customer purchasing behavior, and forecast future sales trends for strategic decision-making.

---

# Business Problem

The retail organization faced several operational and analytical challenges, including:

- Inconsistent sales performance across stores and regions
- Frequent stockouts and excess inventory issues
- Difficulty extracting insights from centralized ERP data
- Reduced profitability due to discount strategies
- Limited visibility into customer purchasing patterns

The project aims to transform raw transactional data into meaningful business intelligence insights.

---

# Project Objectives

- Analyze sales performance across stores, regions, and product categories
- Identify inventory turnover trends and stockout risks
- Evaluate profitability and discount impact
- Understand customer loyalty and purchasing behavior
- Forecast future sales trends for strategic planning

---

# Dataset Information

The project uses three primary datasets:

## 1. Retail Stores Dataset

Contains:
- Store_ID
- City
- State
- Region
- Store Size
- Store Format

## 2. Retail Products Dataset

Contains:
- Product_ID
- Product Category
- Product Subcategory
- Unit Price
- Profit Margin
- Seasonal Flag
- Restock Threshold
- Lead Time

## 3. Retail Transactions Dataset

Contains:
- Transaction_ID
- Date of Sale
- Product_ID
- Quantity Sold
- Total Sales Amount
- Discount Applied
- Inventory Level
- Customer Loyalty Status
- Payment Method
- Lead Time
- Profit Margin

---

# Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Forecasting Analytics
- PowerPoint

---

# Data Modeling

A star schema model was created using:

## Dimension Tables
- Dim_Stores
- Dim_Products
- Dim_Calendar

## Fact Table
- Fact_Transactions

Relationships were established using:
- Store_ID
- Product_ID
- Date

---

# Key KPIs

- Total Sales
- Gross Sales
- Total Profit
- Quantity Sold
- Inventory Turnover Rate
- Stockout Risk Count
- Average Discount
- Annual Revenue

---

# Dashboard Pages

## 1. Executive Overview
- KPI Summary
- Sales Trend Analysis
- Regional Sales Performance
- Product Category Contribution

## 2. Store Performance Analysis
- Store Location Analysis
- Store Format Performance
- Product Subcategory Sales

## 3. Inventory Optimization Analysis
- Inventory Turnover
- Stockout Risk Analysis
- Lead Time Evaluation

## 4. Product & Profitability Analysis
- Gross vs Net Sales
- Seasonal Sales Trends
- Product Profitability

## 5. Customer & Discount Analysis
- Customer Loyalty Analysis
- Payment Method Analysis
- Discount Impact on Sales

## 6. Forecasting & Revenue Analysis
- Sales Forecasting
- Annual Revenue Waterfall Analysis
- Strategic Recommendations

---

# Key Insights

- Southeast region generated the highest sales contribution
- Home Goods emerged as the top-performing product category
- Strip Center stores delivered strong sales performance
- Frequent stockouts were observed in Accessories and Bakery products
- Loyal customers contributed significantly to total sales
- Seasonal demand patterns strongly influenced revenue growth
- Forecasting analysis indicated continued future sales growth

---

# Strategic Recommendations

- Improve inventory planning for high stockout-risk products
- Optimize discount strategies to improve profitability
- Focus business expansion in high-performing regions
- Strengthen customer loyalty programs
- Utilize forecasting insights for demand planning

---

# Project Outcome

The Power BI solution successfully transformed retail ERP data into actionable business insights, enabling:
- Improved operational visibility
- Better inventory management
- Enhanced profitability analysis
- Data-driven strategic decision-making

---

# Author

## Naren Karthik

B.Tech – Computer Science & Business Systems  
Thiagarajar College of Engineering

---

# Dashboard Preview

(Add dashboard screenshots here)

- Executive Overview
- Store Performance Analysis
- Inventory Optimization Analysis
- Product & Profitability Analysis
- Customer & Discount Analysis
- Forecasting & Revenue Analysis
