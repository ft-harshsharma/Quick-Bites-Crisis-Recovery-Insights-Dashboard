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
- MoM Sales %  
- QoQ Sales %  
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
- On-Time Delivery %  
- Late order count  
- SLA buckets (0–25 / 25–50 / 50–75 / 75–100)  

---

## 📊 Dashboard Sections

### **1️⃣ Executive Overview**
- Total orders trend  
- Sales trend  
- AOV  
- Cancellations  
- Sentiment & ratings  
- Month-over-month changes  

---

### **2️⃣ Customer Insights**
- Recovery segmentation (High / Moderate / Low)  
- Customer churn distribution  
- Top cuisines ordered  
- Negative feedback categories  
- Sentiment trend over time  

---

### **3️⃣ Restaurant Insights**
- Composite Decline Scores  
- Top declining restaurants  
- Sentiment banding  
- Cuisine performance  
- Pre vs post crisis revenue  

---

### **4️⃣ Delivery Partner Insights**
- SLA % distribution  
- Delivery partner rating analysis  
- Late order count  
- SLA buckets segmentation  
- Vehicle type & city performance  

---

### **5️⃣ Sentiment & Ratings**
- Sentiment score shift (0.7 → -0.3 post-crisis)  
- Text feedback analysis  
- Cold food, late delivery, food quality spikes  
- Negative review trend  

---

### **6️⃣ Crisis Impact Summary**
- Orders pre/post crisis  
- Revenue shift  
- Delivery SLA collapse (43% → 12%)  
- Negatives reviews surge  
- Restaurant decline distribution  

---

### **7️⃣ Recommended Strategy**

## **Pillar 1 — Customer Recovery**

### 1. Personalized Win-Back Campaigns  
- Target 170 high & 45,237 moderate recoverable customers  
- Send cuisine-based & restaurant-based offers  
- Promote frequently ordered items (lassi, biryani, chai)

### 2. Restore Trust  
- “Hot & Fresh Guarantee”  
- Quality badges  
- Highlight positive-sentiment restaurants  

### 3. Restaurant Recovery  
- Promote top 200 declining food partners  
- Reassess low sentiment restaurants  
- Introduce hygiene & packaging checks  

---

## **Pillar 2 — SLA & Operations Recovery**

### 1. Improve Delivery Workforce  
- Remove low-SLA partners (3.4k in 0–25%)  
- Incentivize mid performers (25–50%)  
- Premium bonuses for 75–100% SLA performers  

### 2. Fix Delivery Operations  
- Thermal packaging rollout  
- Route optimization  
- Peak-hour workforce reinforcement  
- SLA recalibration  

### 3. Packaging & Food Quality  
- Mandatory heat-retaining packaging  
- Replace restaurants with repeated food quality issues  
- Introduce packaging compliance score  

---

## 🚀 Key Insights

### 📉 Delivery Performance Is the Root Cause  
- SLA dropped from 43% → 12%  
- Cold food + late delivery complaints surged  
- Delivery partners heavily skewed to low performance  

### 💬 Customer Sentiment Crashed  
- Sentiment fell from 0.7 → -0.3  
- Negative reviews tripled  
- Food quality & cold food dominated complaints  

### 🧑‍🍳 Restaurants Are Mostly Victims  
- 7,000 affected restaurants  
- Majority have positive sentiment  
- Indicates failure in delivery operations, not food quality  

### 🛵 Delivery Workforce Issues  
- 3.4k riders with <25% SLA  
- Only 301 reliable SLA performers  

### 🛒 Customer Behaviour Changed  
- Drop in ordering frequency  
- Mild dip in AOV  
- Trust erosion across high-value customers  

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

