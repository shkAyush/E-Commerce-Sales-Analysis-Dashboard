# 📊 E-Commerce Sales Analysis Dashboard (Power BI)

![E-Commerce Dashboard](Capture.PNG)

## 📌 Project Overview
This project showcases an **interactive E-Commerce Sales Analysis Dashboard** developed using **Microsoft Power BI**.
The dashboard provides actionable insights into revenue performance, customer behavior, product trends,
and cancellations to support data-driven decision-making.

---

## 🛠 Tools & Technologies
- Microsoft Power BI  
- Power Query (ETL & Data Cleaning)  
- DAX (Data Analysis Expressions)  
- Excel / CSV datasets  

---

## 📂 Dataset Description
The dashboard is built using multiple datasets:
- **Orders** – Order details, revenue, cancellation status  
- **Customers** – Customer-level information  
- **Products** – Product name and category  
- **Sales Metrics** – Revenue, AOV, cancellation rate, lost revenue  

---

## 📈 Key Performance Indicators (KPIs)
- **Total Revenue:** ₹107.47M  
- **Average Order Value (AOV):** ₹112.23K  
- **Cancellation Rate:** 30.36%  
- **Lost Revenue (Cancellation):** ₹44.82M  
- **Total Orders:** 1.357K  

---

## 📊 Dashboard Insights

### 🔹 Revenue by Product Name
- Identifies top-selling products such as laptops and mobiles  
- Helps detect low-performing products  

### 🔹 Revenue by Category
- Category-wise revenue comparison  
- Laptops and mobiles generate the highest revenue  

### 🔹 Revenue by State
- Displays state-wise revenue contribution  
- Maharashtra is the top-performing state  

### 🔹 Revenue by Quarter
- Quarterly revenue trend analysis  
- Significant revenue drop observed in Q4  

### 🔹 Interactive Filters
- Category slicer  
- Date range slicer  
- Enables dynamic data exploration  

---

## 📐 Sample DAX Measures
```DAX
Total Revenue = SUM(sales[revenue])

Average Order Value =
DIVIDE([Total Revenue], [Total Orders])

Cancellation Rate =
DIVIDE(SUM(sales[cancelled_orders]), [Total Orders])

Lost Revenue = SUM(sales[lost_revenue])

## Dashboard Image

<img width="1919" height="987" alt="Capture" src="https://github.com/user-attachments/assets/5d1cccc3-5cea-4846-a7fe-aac750dc5fe3" />
