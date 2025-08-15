# SQL + Power BI Analytics

## Project Overview
This project is designed to help me **practice SQL queries** on a sales dataset and **develop Power BI dashboards** by translating analytical insights into interactive visual reports.

The dataset is sourced from the [Northwind PostgreSQL repository](https://github.com/pthom/northwind_psql/tree/master).

The main objective is to **analyze key business metrics** across multiple dimensions — sales, customers, products, shipping, and profitability — and to visualize them in Power BI for data-driven decision-making.



---

## 📂 Dataset
- **Source:** [Northwind PostgreSQL Dataset](https://github.com/pthom/northwind_psql/tree/master)  
- **Context:** Fictional company selling products worldwide.  

---

## 📈 Analysis Scope

### 1. Sales & Revenue Metrics
- **Total Revenue** = `SUM(UnitPrice * Quantity * (1 - Discount))`
- **Average Order Value (AOV)** = `Revenue / Order Count`
- **Order Count** (total & by month/quarter/year)
- **Sales Growth %** = `(ThisPeriod - LastPeriod) / LastPeriod * 100`
- **Top 10 Products by Sales**
- **Top 5 Customers by Revenue**
- **Revenue by Category / Supplier**
- **Revenue by Region / Country**

---

### 2. Customer Metrics
- **Customer Lifetime Value (LTV)** = Total spend per customer
- **Repeat Customer Rate** = `(Customers with >1 order) / (Total Customers)`
- **New vs Returning Customers** (monthly trend)
- **Top Markets** by revenue

---

### 3. Product & Inventory Metrics
- **Best-Selling Products** (by quantity sold)
- **Most Profitable Products** (by margin)
- **Low Margin Products** = Margin < company target
- **Category Contribution %** = `(Category Revenue / Total Revenue)`

---

### 4. Shipping & Operations
- **Average Delivery Time** = `ShippedDate - OrderDate`
- **Late Shipment Rate** = Orders where `ShippedDate > RequiredDate`
- **Orders per Shipping Method** (Standard vs Express)
- **Shipping Cost % of Revenue**

---

### 5. Profitability Analysis
> *Note: The Northwind dataset doesn’t store cost of goods directly. You can simulate costs or use `UnitPrice - EstimatedCost` if you add a cost column.*

- **Gross Profit** = `Revenue – Cost`
- **Gross Margin %** = `(Gross Profit / Revenue) * 100`
- **Profit by Product, Category, Region**

---

### 6. Time-based Trends
- Monthly Revenue Trend
- Quarterly Revenue & Profit Trend
- Year-over-Year Growth
- Seasonality Patterns (sales spike months)

---

### 7. Power BI KPIs
Recommended KPIs to display on the dashboard:
- Total Revenue (YTD) vs Target (KPI visual)
- Total Orders
- Gross Margin %
- On-Time Delivery %
- Top Category (by sales)
- Best Customer (by revenue)

---

## Tools & Technologies
- **SQL** (PostgreSQL)
- **Power BI** (Data visualization & dashboards)
- **GitHub** (Version control)
- **Northwind Dataset**

