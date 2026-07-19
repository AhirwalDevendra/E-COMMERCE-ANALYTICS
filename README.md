# 📊 E-Commerce Analytics Dashboard (Power BI)

## 🔗 Live Dashboard
👉 https://app.powerbi.com/view?r=eyJrIjoiNjg1ZmRiZTItODA1My00NTI1LWFhNWItNzE1NzAwMjY1NzMyIiwidCI6IjMxMWE4ZTI1LWE0YzEtNDAwOC04YTA3LTgzMTk2YWI1ZDU0MiJ9

---

## 📌 Project Overview
This project is an end-to-end Power BI analytics dashboard 
built on a real-world e-commerce dataset. The dataset spans 
7 related tables including Orders, OrderDetails, Products, 
Customers, Suppliers, Shippers, and Payments connected 
through a star schema with a bridge table relationship between 
Suppliers and Orders resolved using bidirectional cross-filtering.

The dashboard is designed around three core business questions:

  1. Is the business growing and is that growth healthy?
  2. Who are our best customers and how do we retain them?
  3. Which suppliers and shippers are hurting our delivery performance?

Each question maps to one dashboard page, and every visual is 
built to drive a specific business decision not just display data.

---

## 🚀 Key Features

### 🔹 Executive Overview
- Total Orders, Revenue (YTD, MTD)
- Monthly & Quarterly Revenue Trends
- Revenue by Category
- Top 5 Products Analysis
- Revenue Quality Metrics (YoY %, Discount %, AOV)

### 🔹 Customers & Sales
- Total Customers & Revenue per Customer
- Customer Segmentation:
  - Champion
  - Loyal
  - At Risk
  - Occasional
- Monthly Customer Acquisition
- Top 10 Customers by Revenue
- Avg Days to 2nd Purchase

### 🔹 Operations Dashboard
- Delivery Performance Metrics
- On-Time Delivery %
- Average Delivery Days
- Shipper Scorecard
- SLA Metrics (Late Orders, Avg Delay)
- Supplier Dispatch Performance

---

## 📊 Key Insights Derived

### 💰 Revenue & Sales Insights
- Majority of revenue is generated from **Gourmet & World Food and Cleaning categories**
- Strong **quarterly growth trend**, with peak sales in later months
- A small number of products contribute to a **high percentage of total revenue (Pareto effect)**

### 👥 Customer Insights
- High number of **loyal and champion customers**, indicating strong retention
- Very low **at-risk customers**, suggesting good customer satisfaction
- Average **~40 days to second purchase** → opportunity to reduce via remarketing
- Top customers contribute significantly → **focus on VIP retention strategies**

### 📦 Operational Insights
- **On-time delivery is low (~24–25%)**, indicating logistics inefficiency
- High number of **late deliveries (>70%)** impacting customer experience
- Certain shippers consistently underperform → **scope for vendor optimization**
- Average delivery time (~28 days) is relatively high

### 🚚 Supply Chain Insights
- Some suppliers have **faster dispatch times**, indicating performance gaps
- Fulfillment chain shows imbalance → need for **process standardization**
- High delays suggest need for **SLA enforcement and monitoring**

### 📉 Business Risks & Opportunities
- Improve logistics to reduce delivery delays → direct impact on retention
- Target **occasional customers** to convert into loyal segment
- Optimize discount strategy (currently ~11%) to improve margins
- Introduce **predictive analytics for demand & delivery planning**

---

## 📊 KPIs
- Revenue (YTD / MTD)
- Total Orders
- Average Order Value (AOV)
- Customer Segments
- On-Time Delivery %
- Discount %
- Revenue Growth (YoY)

---

## 🛠️ Tech Stack
- Power BI
- Power Query
- DAX
- Excel / CSV

---

## 📈 Business Value
- Identify top-performing categories & products  
- Improve customer retention strategies  
- Monitor operational efficiency  
- Track revenue growth trends  
