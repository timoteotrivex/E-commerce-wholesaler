# 📊 Online Retail Sales Analysis — Power BI

## 📌 Project Overview

This project presents an interactive sales analysis developed in **Microsoft Power BI**, using the **Online Retail** transactional dataset.

The objective was to transform raw transactional data into an interactive Business Intelligence dashboard, applying **data modeling, DAX measures, filters and data visualization** to identify sales patterns and business insights.

The analysis focuses on sales performance across different dimensions such as **time, country, customers, products and transaction behavior**.

---

## 🗂️ Dataset

The dataset contains transactions from an online retail business based in the **United Kingdom**.

The data covers transactions that occurred between **December 1, 2010 and December 9, 2011**.

The company mainly sells **unique gifts for different occasions**, and a significant portion of its customers are wholesalers.

The dataset contains transactional information such as:

- Invoice number
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

---

## 🎯 Project Objectives

The main objectives of this project were:

- Analyze total sales performance
- Identify sales patterns by hour
- Analyze sales by day of the week
- Compare AM vs PM sales
- Analyze sales distribution by country
- Analyze customer behavior
- Evaluate invoice volume
- Analyze average ticket value
- Explore product and pricing behavior
- Build an interactive dashboard for business analysis

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **Data Modeling**
- Data Visualization
- Interactive Filters & Slicers
- Drillthrough
- KPI analysis

---

# 📈 Dashboard

## 1. Executive Dashboard

The executive dashboard provides a high-level overview of the business performance.

It includes key indicators such as:

- Total Amount
- Invoice Count
- Customer Count
- Average Ticket
- Unit Price Average

It also allows users to interact with the data through filters and explore different dimensions of the business.

![Executive Dashboard](Images/Dashboard_Executive.png)

---

## 2. Analysis by Hour

This dashboard analyzes how sales are distributed throughout the day.

The analysis includes:

- Sales by hour
- AM vs PM performance
- Sales by day of the week
- Sales by country
- Hour × Day of Week analysis

One of the main objectives is to identify periods with higher sales concentration and understand how sales behavior changes depending on the day and time.

![Analysis by Hour](Images/Analysis_by_Hour.png)

---

## 3. Analysis by Country

This dashboard analyzes the geographical distribution of sales.

The analysis allows comparison between countries based on:

- Total sales
- Customer volume
- Invoice volume
- Average ticket
- Share of total sales

This helps identify the markets that contribute most significantly to overall revenue.

![Analysis by Country](Images/Analysis_by_Country.png)

---

## 4. Product Analysis

The product analysis focuses on understanding product performance and sales behavior.

The dashboard allows the analysis of:

- Total sales by product
- Quantity sold
- Average unit price
- Product performance
- Top-performing products

![Product Analysis](Images/Product_Analysis.png)

---

## 5. Customer Analysis

Customer-related analysis focuses on understanding the relationship between customers, invoices and sales.

Key indicators include:

- Customer Count
- Invoice Count
- Total Amount
- Average Ticket
- Sales per Customer

![Customer Analysis](Images/Customer_Analysis.png)

---

# 🧮 DAX Measures

Several DAX measures were created to support the analysis and provide dynamic calculations.

Examples include:

- Total Amount
- Invoice Count
- Customer Count
- Average Ticket
- Unit Price Average
- Sales per Customer
- Percentage of Total Sales

The measures were designed to respond dynamically to the different filters and dimensions used throughout the dashboards.

---

# 🔎 Key Analytical Areas

The project explores several business questions:

### ⏰ Time Analysis

- Which hours generate the highest sales?
- How are sales distributed between AM and PM?
- Which days of the week generate the highest revenue?
- Are there specific day/hour combinations with higher sales concentration?

### 🌎 Geographic Analysis

- Which countries generate the highest sales?
- Which countries have the largest customer base?
- How does average ticket vary between countries?

### 👥 Customer Analysis

- How many customers generate the total sales?
- What is the average ticket?
- How much revenue is generated per customer?

### 🛍️ Product Analysis

- Which products generate the highest sales?
- Which products have the highest quantities sold?
- How does unit price relate to sales performance?

---

# 📁 Project Structure

```text
Online-Retail-PowerBI-Analysis/
│
├── PowerBI/
│   └── Online_Retail_Analysis.pbix
│
├── Images/
│   ├── Dashboard_Executive.png
│   ├── Analysis_by_Hour.png
│   ├── Analysis_by_Country.png
│   ├── Product_Analysis.png
│   └── Customer_Analysis.png
│
└── README.md
