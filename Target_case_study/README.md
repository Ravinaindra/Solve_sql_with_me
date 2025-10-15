# 🎯 Target Case Study – MySQL Analysis Project

## 📘 Overview
This project performs a detailed **data analysis on Target's e-commerce dataset (Brazil region)** using MySQL.  
It explores customer behavior, order trends, freight costs, delivery performance, and payment insights to help understand key business metrics and improve operational efficiency.

## 🛠️ Tools & Technologies
- **Database:** MySQL
- **Analysis Tool:** MySQL Workbench
- **Data Source:** Target e-commerce dataset (customers, orders, payments, products, etc.)
- **Languages:** SQL

## 📂 Project Structure
Target_case_study/
│
├── scripts/
│ └── target_case_study_queries.sql # All SQL queries used in the analysis
│
├── data/
│ └── dataset_description.txt # Info about tables & data schema
│
├── report/
│ └── Target_Case_Study_Report.pdf # Full analytical report
│
├── diagrams/
│ └── er_diagram.png # (Optional) ER diagram for the database
│
└── README.md

## 🧩 Key Analytical Sections

### 1️⃣ Data Exploration
- Identified data types for all tables.
- Explored time range of orders (Sept 2016 – Oct 2018).
- Found **4119 cities** and **27 states** involved in customer orders.

### 2️⃣ Trend & Seasonality
- Orders show a **steady upward trend** until Aug 2018.
- **July–August** months have peak order volumes, while **Sept–Dec** are comparatively low.
- Most orders placed in **Afternoon (13–18 hrs)**.

### 3️⃣ State-wise Analysis
- States **SP, RJ, MG** dominate order counts and total revenue.
- SP alone contributes ~40,000 customers.

### 4️⃣ Economic Impact
- **136% increase in total order cost** from 2017 → 2018 (Jan–Aug).
- SP, RJ, MG lead in **total sales** and **freight values**.
- States **PB, AL, AC** have highest average order prices (fewer but high-value purchases).

### 5️⃣ Delivery Performance
- Delays observed between estimated and actual delivery.
- Fastest delivery states: **SP, PR, MG, DF, SC**  
  Slowest delivery states: **RR, AP, AM, AL, PA**
- Focus needed on logistics and delivery optimization.

### 6️⃣ Payment Insights
- Majority of customers prefer **Credit Card** payments.
- Orders with **single installment** are highest.
- Suggests opportunity for **offers or loyalty rewards** on quick payments.

## 💡 Business Recommendations
1. **Payment Promotions:** Partner with banks to provide discounts for single-installment or credit card users.  
2. **State-based Marketing:** Focus marketing in high-order states (SP, RJ, MG) and growth strategies in low-order regions.  
3. **Customer Retention:** Introduce loyalty programs for repeat customers.  
4. **Logistics Optimization:** Improve coordination to reduce delivery delays and freight costs.  
5. **Warehousing:** Establish smaller hubs near high-order cities to reduce freight time and cost.


