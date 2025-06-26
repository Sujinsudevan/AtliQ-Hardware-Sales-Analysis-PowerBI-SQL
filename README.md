[Download Power Bi Report(.pbix)](https://drive.google.com/file/d/1Y8jj9JR3wmJFTtTFvBqknfvE2iOlCHMd/view?usp=sharing)

![image](https://github.com/user-attachments/assets/3e303941-0e58-4468-ba23-ad0df7c8eeaf)

# AtliQ Hardware Sales Analysis

##  Project Overview
This project analyzes the sales performance of **AtliQ Hardware**, a pan-India hardware supplier, using Power BI. The analysis draws from a relational MySQL database, covering transactional data from 2017 to 2020. The main objective is to help the Sales Director make informed decisions by identifying trends, profit drivers, and performance bottlenecks across products, markets, and customers.

---

##  Objectives
- Understand sales trends across time, cities, and zones
- Analyze profit patterns and identify high-margin areas
- Evaluate customer performance, especially among B2B stores
- Track product popularity and underperforming items
- Identify bottlenecks and new business opportunities
- Support data-driven sales forecasting and guestimates

---

##  Tools & Techniques
- **Power BI Desktop** for data modeling and visualization
- **Power Query** for data cleaning and transformation
- **MySQL** for data extraction and exploration
- **DAX** for creating custom KPIs and business logic, including:
  - `Total Revenue`
  - `Total Profit`
  - `Profit Margin %`
  - `Revenue % by Market`
  - `Profit Contribution %`
- **Data Modeling** using a star schema with a central fact table
- **Drill-through functionality** for detailed customer and product-level analysis

---

##  Dataset Description
Data sourced from a MySQL database containing:
- `customers`: Customer details including type and location
- `products`: Product metadata
- `markets`: Market and zone information
- `date`: Time dimension for analysis
- `transactions`: Fact table with sales and cost data

---

##  Key Insights

### 1. Sales Trends
- Sales revenue shows a **steady decline** from 2017–2020, with a **seasonal surge** in July and August likely due to festive demand.

### 2. Revenue by Market
- **Delhi** leads with 52% of total revenue, followed by Mumbai (15%) and Ahmedabad (13%).
- **Top 5 cities contribute over 90%** of revenue, indicating high geographic dependency.

### 3. Profit Margin Insights
- Highest profit margins found in **low-revenue cities**:
  - Surat: 4.86% margin, 0.26% revenue share
  - Patna: 4.12% margin, 0.45% revenue share
  - Bhubaneswar: 3.98% margin, 0.09% revenue share
- These cities are **under-penetrated high-margin opportunities**.

### 4. Profit vs Revenue Anomaly
- **Bhopal** contributes 5.9% of revenue but 9.3% of profit.
- Suggests **higher operational efficiency** in Bhopal.

### 5. Zone-Level Performance
- **North Zone**: 68% revenue, but lowest profit margin (2.2%)
- **Central Zone**: 26% revenue with highest margin (3.2%)
- Indicates need to **optimize North zone costs** and **expand Central zone operations**

### 6. Customer Insights
- **Electricalsara Stores** alone contributes 41% of total revenue.
- High **customer concentration risk** — dependency on a single client.

---

##  Recommendations
- **Expand operations in high-margin cities** like Surat, Patna, and Bhubaneswar.
- **Double down on Bhopal** — optimize marketing and logistics to capitalize on its profitability.
- **Review cost structures** in Delhi and across the North zone to improve margins.
- **Diversify the customer base** — reduce reliance on a single B2B client by targeting new hardware stores and distributors.

---

