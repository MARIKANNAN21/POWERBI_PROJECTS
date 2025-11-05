# 📦 Amazon Sales Descriptive Data Analysis (Power BI Project)

---

## 🧩 Problem Statement / Key Questions

This project focuses on understanding and visualizing Amazon order data through descriptive data analysis.  
The analysis answers the following key business questions:

1. **Sales Overview**  
   ➤ *How are our total sales and average order values trending across time?*

2. **Orders & Fulfilment Overview**  
   ➤ *What proportion of orders are shipped, cancelled, or fulfilled by Amazon vs Merchant?*

3. **Product Performance Overview**  
   ➤ *Which products, categories, and sizes drive the highest sales and order volumes?*

4. **Promotional & Channel Overview**  
   ➤ *How do promotions and sales channels (B2B vs Retail) impact total revenue and order value?*

5. **Geography Overview**  
   ➤ *Which states and cities contribute the most to sales, and where are growth opportunities?*

---

## 🎯 Project Objective

To perform **descriptive data analysis** on Amazon order data and uncover:
- Trends in overall **sales and order performance**
- **Fulfilment efficiency** between Amazon and Merchant channels
- **Product demand patterns** across categories and sizes
- **Impact of promotions** and **B2B vs Retail** segmentation
- **Regional sales distribution** for market expansion opportunities

---

## 🧾 Data Overview

The dataset contains detailed transactional records from Amazon’s order system, including order, shipment, and product attributes.

| Column | Description |
|---------|-------------|
| **Order ID** | Unique order identifier |
| **Date** | Order placement date |
| **Status** | Current order status (Shipped, Cancelled, Delivered) |
| **Fulfilment** | Who fulfilled the order (Amazon / Merchant) |
| **Sales Channel** | Platform where the order was placed (Amazon.in) |
| **ship-service-level** | Shipping method (Standard / Expedited) |
| **SKU** | Unique product identifier |
| **Category** | Product category (Kurta, Set, Dress, etc.) |
| **Size** | Product size |
| **Qty** | Quantity ordered |
| **Amount** | Order amount (INR) |
| **ship-city / state / postal-code** | Delivery location |
| **promotion-ids** | Promotion codes applied |
| **B2B** | Business-to-Business indicator |
| **fulfilled-by** | Fulfilment method (Easy Ship, FBA, Self Ship) |

---

## 🧰 Tools & Technologies Used

| Tool / Tech | Purpose |
|--------------|----------|
| **Microsoft Power BI** | Data modeling, dashboard creation, and visualization |
| **Power Query Editor** | Data cleaning & transformation |
| **DAX (Data Analysis Expressions)** | Creating KPIs & calculated measures |
| **Microsoft Excel** | Initial data exploration & verification |

---

## 📊 Page-wise Explanation & Key Insights

### 🔹 **1. Sales Overview**
**Visuals:** KPI Cards, Line Chart, Donut Chart  
**KPIs:** Total Sales, Total Orders, Total Quantity, Average Order Value  

📈 **Insight:**  
Sales show consistent month-on-month growth, with notable seasonal spikes during promotional periods.

---

### 🔹 **2. Orders & Fulfilment Overview**
**Visuals:** 100% Stacked Column Chart, Donut Chart, KPI Cards  
**KPIs:** Fulfilment Share (Amazon vs Merchant), Cancellation Rate, Shipped Orders %  

🚚 **Insight:**  
68% of total orders are fulfilled by Amazon (FBA/Expedited), showing higher reliability and lower cancellation rates compared to Merchant-fulfilled orders.

---

### 🔹 **3. Product Performance Overview**
**Visuals:** Treemap, Clustered Bar Chart, Column Chart  
**KPIs:** Sales by Category, Sales by Size, Top 10 SKUs  

🛍️ **Insight:**  
Kurta category dominates sales share; Size XL records the highest demand volume, indicating strong preference in apparel sizing.

---

### 🔹 **4. Promotional & Channel Overview**
**Visuals:** Clustered Column Chart, Pie Chart  
**KPIs:** Promo vs Non-Promo Orders, B2B vs Retail Split, Promo Revenue %  

💡 **Insight:**  
Promotional orders contribute ~40% of total revenue, while B2B customers generate 25% higher average order values than retail customers.

---

### 🔹 **5. Geography Overview**
**Visuals:** Filled Map, Bar Chart, Table  
**KPIs:** State-wise Sales, City-wise Orders  

🌍 **Insight:**  
Maharashtra, Karnataka, and Tamil Nadu are top-performing states. Tier-2 cities like Chandigarh and
