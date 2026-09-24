# 🍽️ Restaurant Analytics Dashboard – Power BI

## 📊 Project Overview

This project is an interactive Power BI dashboard designed to analyze restaurant business performance across sales, customers, orders, revenue, delivery operations, and restaurant-level performance.

The objective of this project is to transform raw restaurant data into meaningful business insights that can support data-driven decision making.

---

## 🎯 Business Objectives

The dashboard focuses on answering the following business questions:

- How much revenue is being generated?
- How many orders are being placed?
- How are new and returning customers behaving?
- Which customer segments generate the most orders?
- What are the revenue trends over time?
- What is the average order value?
- What is the average delivery time?
- What percentage of orders are delivered, cancelled, or delayed?
- Which restaurants/customers contribute the most revenue?
- How does restaurant performance change over time?
- What customer trends can help improve retention?

---

# 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- KPI Analysis
- Business Intelligence

---

# 📁 Dashboard Pages

## 1. Executive Overview

The Executive Overview provides a high-level summary of restaurant business performance.

### Key Metrics

- Total Revenue
- Total Orders
- Average Order Value
- Average Delivery Time
- Average Rating
- Customer Metrics

### Visualizations

- Revenue KPIs
- Order KPIs
- Revenue Trends
- Order Trends
- Customer Segmentation
- Restaurant Performance

---

## 2. Customer Analytics

This page focuses on customer behavior and customer segmentation.

### Key Analysis

- New vs Returning Customers
- Customer Type
- Top Customers
- Orders by Customer Type
- Customer Revenue
- Customer Order Frequency
- Customer Signup Trends

### Key Metrics

- Total Customers
- Returning Customers
- Repeat Customer %
- Orders per Customer
- Customer Revenue

---

## 3. Restaurant Performance

This page analyzes restaurant-level performance.

### Analysis

- Restaurant Revenue
- Restaurant Orders
- Average Rating
- Customer Demand
- Restaurant Performance Trends
- Revenue Contribution

---

## 4. Delivery & Operations

This page analyzes delivery and operational performance.

### Key Metrics

- Average Delivery Time
- Delivered Orders
- Cancelled Orders
- Delayed Orders
- Total Orders
- Delivery Status

### Visualizations

- Delivery Status Distribution
- Order Trends
- Revenue Trends
- Customer Order Distribution

---

## 5. Advanced Insights

This page provides deeper analysis of business performance and customer behavior.

The analysis focuses on:

- Customer segmentation
- Revenue patterns
- Order frequency
- Customer contribution
- Operational performance
- Trend analysis

---

## 6. Restaurant Details

This page provides detailed restaurant-level information.

### Key Metrics

- Total Revenue
- Average Delivery Time
- Average Votes
- Average Rating
- Total Orders

Restaurant-level trends are also analyzed using order and revenue charts.

---

# 📈 Key KPIs

| KPI | Description |
|---|---|
| Total Revenue | Total revenue generated |
| Total Orders | Total number of orders |
| Average Order Value | Average revenue per order |
| Average Delivery Time | Average time required for delivery |
| Average Rating | Average customer rating |
| Total Customers | Total unique customers |
| Returning Customers | Customers who placed repeat orders |
| Repeat Customer % | Percentage of customers returning |
| Orders per Customer | Average orders generated per customer |

---

# 🔍 Key Insights

### Customer Insights

- Customer behavior can be segmented into New, Returning, and Premium customers.
- Returning customers provide an important opportunity for customer retention analysis.
- Top customers can be identified based on revenue and order frequency.

### Sales Insights

- Revenue and order trends can be monitored over time.
- Customer segments contribute differently to total order volume.
- High-value customers can be identified for targeted retention strategies.

### Operational Insights

- Delivery status analysis helps identify delivered, cancelled, and delayed orders.
- Average delivery time provides an important operational KPI.
- Monitoring delivery performance can help identify operational bottlenecks.

---

# 💡 Business Recommendations

Based on the dashboard analysis:

1. Focus on improving customer retention and repeat purchases.
2. Identify high-value customers and develop targeted loyalty strategies.
3. Monitor delivery delays and cancellation patterns.
4. Analyze high-performing restaurants to understand factors contributing to revenue.
5. Track revenue and order trends regularly to identify changes in demand.
6. Use customer segmentation for targeted marketing campaigns.
7. Monitor average delivery time as an operational KPI.

---

# 🧮 DAX & Data Analysis

The project uses DAX measures for calculating business KPIs and analytical metrics.

Examples include:

- Total Revenue
- Total Orders
- Average Order Value
- Average Delivery Time
- Average Rating
- Customer Count
- Returning Customer Count
- Repeat Customer Percentage
- Orders per Customer

---

# 🔄 Data Preparation

The data preparation process included:

1. Data import
2. Data cleaning
3. Handling missing values
4. Data type correction
5. Data transformation using Power Query
6. Creating calculated columns where required
7. Creating relationships between tables
8. Creating DAX measures
9. Building interactive visualizations
10. Validating KPIs and dashboard results

---

# 📊 Dashboard Preview

## Executive Overview

![Executive Overview](Screenshots/executive-overview.png)

---

## Customer Analytics

![Customer Analytics](Screenshots/customer-analytics.png)

---

## Restaurant Performance

![Restaurant Performance](Screenshots/restaurant-performance.png)

---

## Delivery & Operations

![Delivery Operations](Screenshots/delivery-operations.png)

---

## Advanced Insights

![Advanced Insights](Screenshots/advanced-insights.png)

---

## Restaurant Details

![Restaurant Details](Screenshots/restaurant-details.png)

---

# 📂 Project Structure

```text
Restaurant-Analytics-PowerBI/
│
├── PowerBI/
│   └── Restaurant_Analytics_Dashboard.pbix
│
├── Screenshots/
│   ├── executive-overview.png
│   ├── customer-analytics.png
│   ├── restaurant-performance.png
│   ├── delivery-operations.png
│   ├── advanced-insights.png
│   └── restaurant-details.png
│
├── Dataset/
│   └── restaurant_dataset.csv
│
├── Documentation/
│   ├── Project_Overview.pdf
│   ├── Data_Dictionary.xlsx
│   └── DAX_Measures.txt
│
└── README.md
