# Olist E-Commerce Business Discovery & Data Analysis
*HVIA Data & AI Internship | Task 01*

## 📊 Project Overview & Executive Summary
This project is part of the **HVIA Data & AI Internship** program[cite: 3]. It dives deep into the real-world **Brazilian E-Commerce Public Dataset by Olist** (~100,000 orders from 2016 to 2018)[cite: 3]. 

Instead of treating this purely as a technical exercise, the project adopts a **Business Analyst approach**[cite: 3]. We transformed raw tables into actionable operational insights—investigating supply chain friction, pinpointing geographic bottlenecks, and uncovering how delivery delays directly destroy customer trust and platform reputation.

---

## 📈 What We Did & Key Insights (The Data Story)
1. **Data Engineering & Granularity Management:**
   * Integrated 9 complex relational datasets (customers, sellers, orders, items, payments, reviews, products, geolocation, and category translations) into a clean, unified Master DataFrame (`df_master`)[cite: 3].
   * Fixed order-item level inflation by aggregating at the unique `order_id` level to ensure accurate business volumes and rates.
2. **The Satisfaction Cliff (Lateness Impact):**
   * *On-time deliveries* maintain an exceptionally high average customer review score of **4.29 / 5**.
   * *Late orders* cause customer satisfaction to plummet dramatically to **2.57 / 5**, proving that delivery punctuality is the single most critical factor for customer retention.
3. **Revenue Drivers vs. Operational Friction:**
   * High-revenue product categories (such as *Health & Beauty*, *Bed Bath Table*, and *Watches & Gifts*) suffer the highest volume of logistical bottlenecks, highlighting severe supply chain stress under high demand.
4. **Geographic & Seller Concentration Risk:**
   * Shifted from absolute counts to **Late Rates (%)** to fairly evaluate regional performance and identified that a small percentage of underperforming sellers drive a disproportionate share of delivery failures.

---

## 🔗 Links & Resources
* **My Kaggle Notebook:** [Shahd's Olist Analysis Notebook](https://www.kaggle.com/code/shahdtoutou/notebook5010523aaa)
* **Dataset Source:** [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)[cite: 3]

---

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy)
* **Data Visualization** (Matplotlib, Seaborn)
* **Environment** (Jupyter / Kaggle Notebooks)

---
*Developed with passion as part of the HVIA Data & AI Internship.*
