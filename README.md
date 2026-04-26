# 📊 Databricks Lakehouse Sales Analytics Project (End-to-End BI Workflow)

## 🔍 Overview

This project demonstrates an end-to-end analytics workflow using Databricks, simulating how modern data teams operate on a Lakehouse architecture.

The goal is to explore raw data, generate business insights, build dashboards, and enable natural language querying using AI.

---

## 🏗️ Architecture

* Data Platform: Databricks Lakehouse
* Data Model: Star Schema

### Tables Used:

* `fact_sales`
* `dim_customers`
* `dim_products`

📌 *(Add your data model screenshot in /data-model folder and reference here)*

---

## 🔍 Data Exploration (SQL)

Performed detailed exploratory analysis using Databricks SQL Editor:

### Key Analysis:

* Customer distribution by country
* Product hierarchy (category → subcategory → product)
* Sales trends over time
* Category-wise performance

📁 SQL scripts available in `/sql` folder

---

## 📊 Sales Dashboard

### Key Metrics:

* Total Sales
* Total Profit
* Total Quantity

### Visuals:

* Monthly Sales Trend (Line Chart)
* Sales by Category (Bar Chart)
* KPI Summary Cards

### Key Insights:

* Technology category contributes highest revenue
* Sales show clear monthly trends indicating seasonality
* A few categories dominate overall revenue contribution

📌 *(Add screenshot: /dashboards/sales_dashboard.png)*

---

## 👥 Customer Dashboard

### Key Metrics:

* Total Customers
* Average Sales per Customer
* Total Orders

### Visuals:

* Orders by Age Group
* Top 10 Customers by Sales
* Customer Distribution

### Key Insights:

* A small group of customers contributes a large share of revenue (Pareto principle)
* Adult age group drives the majority of orders
* High-value customers can be targeted for retention strategies

📌 *(Add screenshot: /dashboards/customer_dashboard.png)*

---

## 🤖 AI-Powered Analytics (Genie)

Implemented natural language querying using Databricks Genie.

### Sample Questions:

* Top 5 customers by sales
* Sales trend over last 6 months
* Which category generated highest profit?
* Orders distribution by age group

### Approach:

* Reviewed generated SQL queries
* Identified incorrect joins and aggregations
* Improved Genie instructions for better accuracy

### Key Learning:

AI-generated insights must be validated with domain knowledge and proper data modeling.

📁 Details available in `/genie-ai/genie_queries.md`

---

## 🧠 Key Business Insights

* Technology category is the primary revenue driver
* Customer revenue distribution follows the Pareto principle (top customers drive majority sales)
* Sales trends indicate seasonal patterns
* Customer segmentation can improve targeted marketing

---

## 🛠️ Tools & Technologies

* Databricks (SQL, Dashboards, Genie AI)
* SQL (Data Exploration & Transformation)
* Lakehouse Architecture

---

## 💼 Business Use Case

This project simulates how organizations analyze:

* Sales performance
* Customer behavior
* Product trends

to support strategic decision-making.

It reflects a real-world workflow where:
Raw Data → SQL Analysis → Dashboards → AI-driven Insights

---

## 🚀 How to Run This Project

1. Load datasets into Databricks
2. Open SQL Editor and run queries from `/sql`
3. Build dashboards using saved queries
4. Enable Genie AI and test natural language queries

---

## 📂 Repository Structure

```
databricks-lakehouse-sales-analytics/
│
├── sql/
├── dashboards/
├── data-model/
├── genie-ai/
└── README.md
```
---

## 🎯 Key Learnings

* Translating business problems into SQL queries
* Designing dashboards for different stakeholders
* Validating insights with data
* Enhancing analytics using AI tools

---

## 🔗 Future Enhancements

* Integrate with Power BI for enterprise reporting
* Add advanced KPIs (Customer Lifetime Value, Retention)
* Optimize queries for performance
* Automate data pipelines

---

## 🙌 Acknowledgement

This project is based on a hands-on analytics workflow inspired by the training and guidance provided by Baraa Khatib.

His structured approach to teaching Databricks, SQL, dashboards and real-world analytics use cases helped shape the foundation of this project.

This implementation represents my own hands-on work, adaptations, and business-oriented enhancements built on top of the original learning content.

Special thanks for making complex concepts simple and practical.

---

## 📢 Connect With Me

If you found this useful or want to collaborate, feel free to connect.

---
