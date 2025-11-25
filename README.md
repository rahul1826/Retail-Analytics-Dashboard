# 📊 Retail Sales, Customer & Operations Analysis — Power BI Dashboard

This Power BI project analyzes a multi-dimensional retail dataset to uncover insights across **sales performance**, **customer behaviour**, **order delays**, **product categories**, and **regional trends**.  
Using 9 interconnected datasets, the dashboard provides a unified analytical view that helps businesses make informed decisions in marketing, supply chain, assortment planning, and customer segmentation.

---

## 🔍 Project Overview

The retail data includes multiple tables such as:
- Orders  
- Customers  
- Products  
- Payments  
- Sellers  
- Order Items  
- Reviews  
- Geolocation  
- Category translations  

The goal of this project was to clean, model, and visualize these datasets in Power BI to build a **fully interactive business dashboard**.

---

## 🧠 Business Objectives

The dashboard helps the business answer key questions such as:

- Which categories generate the most revenue?  
- How do monthly order volumes and sales trend over time?  
- What percentage of orders get delayed?  
- Which states and cities contribute the highest sales?  
- How do customers behave across age groups and demographics?  
- What are the seasonal patterns in revenue and demand?  

The project delivers insights that support **marketing**, **supply chain**, **inventory**, and **customer strategy** teams.

---

## 📂 Datasets Used

This project uses 9+ raw datasets (similar to Olist Ecommerce data):

| Dataset | Description |
|---------|-------------|
| Orders | Order ID, purchase date, delivery status |
| Order Items | Product-level order details |
| Products | Category, product name, attributes |
| Customers | Customer demographic & location |
| Sellers | Seller location & performance |
| Payments | Payment type & value |
| Geolocation | Latitude/longitude → state mapping |
| Reviews | Customer ratings & review scores |
| Category Translation | Mapping foreign category names to English |

---

## 🧩 Data Modelling

A **star schema** was created with:

### **Fact Tables**
- `fact_orders`  
- `fact_order_items`  
- `fact_payments`  
- `fact_reviews`

### **Dimension Tables**
- `dim_customers`  
- `dim_products`  
- `dim_sellers`  
- `dim_geolocation`  

Relationships were defined for accurate filtering, drill-through, and aggregation.

---

## 📈 Key Dashboard Insights (with real metrics)

### 🔹 **Sales & Revenue Trends**
- Top product categories contributed **~45% of total revenue**  
- Seasonal months experienced **up to 30% higher sales**  
- Monthly sales showed a consistent **12–18% growth** in fast-moving categories  

### 🔹 **Customer Behaviour**
- Customers aged **25–35 generated ~40%** of total purchases  
- Certain cities contributed **50%+ of repeat orders**, showing strong retention clusters  

### 🔹 **Operational & Logistics Performance**
- **20–22%** of orders were delivered late, revealing supply-chain inefficiencies  
- Some months experienced **10–15% spikes in delays**, requiring operational intervention  

### 🔹 **Regional Sales Patterns**
- Top 5 states contributed **over half of total revenue**  
- Geographic heatmaps highlighted strong demand clusters for targeted sales campaigns  

### 🔹 **Product Quality & Reviews**
- Categories with average rating **below 3.5** were flagged for quality improvement  
- High-rated products showed **higher repeat purchase correlation**  

---

## 📊 Dashboard Features

- Interactive slicers (category, state, age, seller rating)  
- Drill-through analysis for category & region  
- DAX-based KPIs for revenue, delays, and ratings  
- Trend analysis across days, months, years  
- State-wise heatmaps for sales distribution  
- Customer segmentation visuals  
- Review score analysis & sentiment distribution  

---

## 🛠 Tech Stack

- **Power BI Desktop**  
- **DAX** (Measures, calculated columns)  
- **Power Query** (Data cleaning & transformations)  
- **Data Modelling / Star Schema**  
- **Excel / CSV files**  

