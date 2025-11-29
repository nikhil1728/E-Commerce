# 🛒 Target Brazil – SQL Analytics using BigQuery

## 📌 Business Context
Target is a globally recognized retail brand.  
This case study focuses on **Target’s e-commerce operations in Brazil**, analyzing ~**100,000 orders (2016–2018)** to understand customer behavior, sales performance, logistics efficiency, and payment patterns.

The analysis was conducted using **Google BigQuery (SQL)** on multiple relational tables.

📄 **Solution Document (PDF):**  
https://github.com/nikhil1728/E-Commerce/blob/main/E-Commerce.pdf

---

## 🎯 Business Objective
As a Data Analyst at Target, the goal is to:
- Explore and understand e-commerce operations in Brazil
- Identify demand trends, seasonality, and customer behavior
- Analyze pricing, freight, delivery performance, and payments
- Generate **actionable, data-driven recommendations** for business optimization

---

## 🗂 Dataset Description
The dataset consists of **8 relational CSV files**, each representing a business dimension:

- `customers`
- `orders`
- `order_items`
- `payments`
- `reviews`
- `products`
- `sellers`
- `geolocation`

### 🌍 Data Coverage
- **Region:** Brazil  
- **Time Period:** 2016 – 2018  
- **Orders:** ~100,000  
- **Data Model:** Relational (joins using `order_id`, `customer_id`, `seller_id`, `product_id`)

---

## 🔍 Initial Data Exploration
- Checked table schemas and column data types
- Identified order date range using `order_purchase_timestamp`
- Counted customer **cities and states**
- Verified relationships between tables using joins

---

## 📈 In-Depth Analysis & Insights

### 1️⃣ Order Trend & Seasonality
- Strong **year-on-year growth** in order volume
- **Monthly seasonality** observed:
  - Peak months: **May–August**
  - Additional spikes during **January–March**
- Confirms strong growth potential for e-commerce in Brazil

---

### 2️⃣ Customer Purchase Time Behavior
Orders were categorized as:
- **Dawn:** 0–6 hrs
- **Morning:** 7–12 hrs
- **Afternoon:** 13–18 hrs
- **Night:** 19–23 hrs

📊 **Observation:**
- Majority of orders placed during **Afternoon & Night**

✅ **Action:**  
Optimize promotions, customer support, and inventory during peak hours

---

### 3️⃣ State-wise E-commerce Growth
- States like **SP, RJ, MG** consistently lead in order volume
- States such as **AC, AP, RR, RO** show low penetration

✅ **Recommendation:**
- Strengthen logistics & inventory in high-demand states
- Launch targeted marketing campaigns in underperforming regions

---

### 4️⃣ Revenue & Economic Impact
- **Jan–Aug 2017 → Jan–Aug 2018:** ~**137% growth** in order value
- Indicates rising customer trust and online adoption

✅ **Business Insight:**  
Brazil is a high-growth market worth long-term investment

---

### 5️⃣ Price & Freight Analysis
- High **average freight costs** observed in states like PB, RR, CE
- High-revenue contribution from states like SP, MG, PR

✅ **Actions:**
- Partner with local logistics providers
- Optimize warehouse & fulfillment locations
- Reduce freight cost to improve profitability

---

### 6️⃣ Delivery Performance Analysis
Calculated:
