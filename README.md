# QuickBites Crisis Recovery & Insights Dashboard

## 📌 Project Overview
In June 2025, QuickBites — a major food delivery platform — experienced a severe reputational and operational crisis. This led to a sharp drop in orders, revenue, customer sentiment, and delivery performance across India.

This project presents a **complete analytics and strategy solution** built in **Power BI**, supported by a clean **star schema**, **DAX measures**, and **segmented insights** across customers, restaurants, delivery partners, and sentiment.

The dashboard enables leadership to answer:
- What went wrong?
- Who was affected?
- How badly?
- How do we recover?

---

## 🎯 Objectives
1. Diagnose the **impact of the June 2025 crisis**.
2. Measure **customer churn, recoverability, sentiment, and ordering patterns**.
3. Analyse **SLA performance**, delivery partner efficiency and decline.
4. Assess **restaurant declines**, sentiment, cuisine performance.
5. Recommend a **data-backed recovery strategy**.
6. Build a scalable **Power BI analytical model** using advanced DAX.

---

## 🧩 Dataset Overview

### **Fact Tables**
- `fact_orders` — Revenue, cancellations, SLA, delivery partner ID  
- `fact_order_items` — Item-level breakdown  
- `fact_delivery_performance` — Actual vs expected delivery time, distance  
- `fact_ratings` — Review text, sentiment score, feedback category  

### **Dimension Tables**
- `dim_customers` — city, category, recovery tag  
- `dim_restaurants` — metadata, partner type, sentiment  
- `dim_delivery_partners` — SLA %, orders, city, vehicle  
- `dim_menu_items` — cuisine, category  
- `dim_date` — hierarchy for time intelligence  

### **Data Size**
- 18,000+ food partners  
- 28,820 active customers  
- 3,400 delivery partners  
- Hundreds of thousands of orders  

---

## 🛠️ Power BI Modeling & Key DAX Measures

### **Time Intelligence Measures**
- Vs last Month %  
- Vs last Quarter %  
- Last 3 Months vs Previous 3 Months
- Pre-Crisis vs Post-Crisis performance  

### **Customer Measures**
- Recovery segmentation  
- Order frequency  
- Customer sentiment trends  
- Negative sentiment count  

### **Restaurant Measures**
- Composite Decline Score  
- Revenue contribution pre/post crisis  
- Sentiment banding  
- Decline segmentation buckets  

### **Delivery Partner Measures**
- SLA %    
- Late order count  
- SLA buckets ( 0 / 1–25 / 25–50 / 50–75 / 75–100)  

---

## 📊 Dashboard Sections

### **1️⃣ Executive Overview and Customer Insights**
- Total orders trend  
- Sales trend  
- AOV, ADS
- Cancellations  
- Sentiment & ratings  
- Month-over-month changes
- Recovery segmentation (High / Moderate / Low)  
- Customer churn distribution  
- Top cuisines ordered  
- Negative feedback categories  
- Customer detail table 

---

### **2️⃣ Food Partner Insights**

- Total and Active Food Partners
- Restaurants and Cloud Kitchen
- Food Partners across cities
- All Cuisines
- Composite Decline Scores  
- Top declining restaurants  (Decline Distribution across Food Partners)
- Sentiment banding  
- Food Item performance  
- Pre vs post crisis revenue
- Food Partners detail table

---

### **3️⃣ Delivery Partner Insights**

- Delivery Partners (Active, Full-Time, Part-Time, Contract )
- Overall SLA (Total Orders, On-time Orders, Late Orders)
- Delivery Partners vehicle type
- Delivery Partners per city
- SLA % Trend and Distribution  
- Negative Feedback Trend
- Delivery Partner detail table

---



---

## 🚀 Key Insights

### 🟥 A. DELIVERY FAILURE — PRIMARY DRIVER
- SLA dropped **from 43% → 12%** post-crisis.
- High concentration of **low-performing delivery partners**.
- Sharp increase in **late delivery complaints**.
- Strong **cold food + late delivery correlation**.
- Delivery inefficiency appears to be the **primary root cause** of the crisis impact.

---

### 🟧 B. FOOD QUALITY FAILURE — SECONDARY DRIVER
- Surge in **Bad Food Quality**, **Cold Food**, and **Packaging Issues** complaints — even from **active loyal customers**.
- However, the **majority of food partners have positive sentiment**, indicating:
  - They were **not** the main cause.
  - Their perceived quality suffered because delivery delays **amplified dissatisfaction**.
- Food issues acted as a **secondary accelerator**, not the origin point.

---

### 🟦 C. CUSTOMER TRUST COLLAPSE
- **Ratings fell sharply** after the crisis.
- **Repeat order frequency** declined significantly.
- Customer sentiment score dropped **from +0.7 → –0.3**.
- Trust erosion became a **compounding effect** driven primarily by poor delivery experience.

---


---

## 📦 Technologies Used
- **Power BI**  
- **Power Query**  
- **DAX**  
- **Python (optional)**  
- **Excel**  
- **Star Schema Modeling**  
- **Text Sentiment Classification**  

---

## 📁 Project Structure

