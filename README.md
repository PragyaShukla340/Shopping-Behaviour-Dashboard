# 🛍️ Shopping Behavior Dashboard – Power BI

### 🎯 **Executive Summary**

This Power BI project transforms raw **shopping behavior data** into **actionable business insights** — uncovering customer purchasing trends, loyalty dynamics, and seasonal performance patterns that drive smarter marketing and retail strategies.

Built using the **`shopping_behavior.csv`** dataset and tools like **Power BI**, **Excel**, and **DAX**, the dashboard highlights how data storytelling can reveal real-world business opportunities.

---

## 📊 **Project Overview**

This dashboard uncovers patterns in customer shopping behavior, helping businesses understand **who their customers are, what they buy, when they buy, and how loyal they are**.  
It transforms raw transactional data into actionable insights — revealing customer trends, category performance, and loyalty dynamics that can directly influence marketing and sales strategies.

---

## 🚀 **Dashboard Objectives**

* Identify **top-performing product categories** and their contribution to total orders and revenue.  
* Evaluate **customer loyalty** and the conversion of one-time buyers into repeat customers.  
* Understand **how demographics** (age, gender) influence purchase behavior.  
* Examine **seasonal spending patterns** and their impact on sales volume.  
* Assess **customer satisfaction** using average review ratings and purchase frequency.

---

## 💡 **Key Insights & Observations**

### 🧾 **1. Sales Performance**
* The platform recorded **over 100K total orders** with a strong **4K active customer base**.  
* The **average order value ($59.76)** and **review rating (3.75/5)** indicate a healthy balance between sales volume and customer satisfaction.  
* **Clothing** emerged as the **dominant category**, driving nearly half of total sales volume, while **accessories** and **footwear** followed at a moderate pace.

---

### 🔄 **2. Customer Loyalty & Funnel**
* The **Customer Funnel** visualization shows a healthy retention ratio, with **31% loyalty conversion** — meaning roughly one in three customers transitioned from first-time buyers to repeat or loyal customers.  
* This indicates **effective re-engagement strategies**, but also highlights scope for loyalty program optimization to push this conversion toward 40–45%.

---

### 👥 **3. Demographic Insights**
* **Male customers** formed the majority of total orders, while females displayed slightly higher average purchase values.  
* The **31–50 age bracket** contributed the most in both revenue and customer count, emphasizing the importance of targeting this segment for future campaigns.  
* The **under-30 group** represents an emerging customer base with high order frequency but smaller basket sizes — ideal for personalized upselling.

---

### 🌦️ **4. Seasonal & Behavioral Trends**
* Spending peaks were observed during **Summer and Winter**, correlating with typical apparel cycles and festive demand.  
* **Quarterly and monthly shoppers** form the bulk of loyal customers, reinforcing that consistency drives retention.  
* The correlation between **review ratings and purchase amounts** showed that higher spenders tend to leave slightly better ratings — a subtle indicator of product satisfaction at premium tiers.

---

### 🧩 **5. Product-Level Insights**
* The **Top 10 Products Table**, enhanced with images, allows a quick scan of high-performing SKUs.  
* **Blouses, Shirts, and Dresses** consistently ranked in the top 3 across both orders and total revenue.  
* Interestingly, even products with **average review scores (3.6–3.8)** performed well, suggesting that **brand trust and category popularity** may outweigh marginal rating differences.

---

## 📈 **Business Implications**

* **Customer Loyalty Program:** Focus on repeat purchase incentives and tiered rewards to push conversion above 40%.  
* **Marketing Optimization:** Allocate marketing spend toward **female customers aged 31–50** with campaigns emphasizing premium collections.  
* **Seasonal Promotions:** Plan major sales around **Summer and Winter**, while testing limited campaigns in Spring and Fall to stabilize off-season revenue.  
* **Product Strategy:** Maintain strong stock levels in **Clothing and Accessories**, while improving visibility for **Footwear and Outerwear** categories.  
* **Customer Experience:** The modest review average (3.75) suggests room for improvement — consider better post-purchase support or review engagement.

---

## 🧭 **Dashboard Navigation**

| Page                    | Focus                  | Description                                      |
| ----------------------- | ---------------------- | ------------------------------------------------ |
| **Overview**            | Business Summary       | Key KPIs, funnel, demographics, and top products |
| **Customer Insights**   | Demographics           | Age, gender, and loyalty-driven trends           |
| **Product Insights**    | Category & Product Mix | Sales distribution and product-level analysis    |
| **Regional Insights**   | Geographic Patterns    | Customer and sales density by location           |
| **Behavioral Insights** | Engagement & Retention | Frequency, seasonality, and promo code analysis  |

---

## 🧮 **Core Measures (DAX)**

| Measure                   | Formula                                                   |
| ------------------------- | --------------------------------------------------------- |
| **Total Sales**           | `SUM('shopping_behavior_updated'[Purchase Amount (USD)])` |
| **Total Orders**          | `COUNTROWS('shopping_behavior_updated')`                  |
| **Total Customers**       | `DISTINCTCOUNT('shopping_behavior_updated'[Customer ID])` |
| **Average Order Value**   | `[Total Sales] / [Total Orders]`                          |
| **Loyalty Conversion %**  | `DIVIDE([Loyal Customers],[Total Customers])`             |
| **Average Review Rating** | `AVERAGE('shopping_behavior_updated'[Review Rating])`     |

---

## 🧠 **Conclusion**

This dashboard bridges **data storytelling and business decision-making**.  
By combining demographics, transaction behavior, and loyalty patterns, it reveals where the brand performs best — and where it can grow next.  

It serves as both a **strategic performance monitor** for leadership and a **diagnostic tool** for marketing and sales teams to align decisions with measurable customer insights.

---

## 🧑‍💻 **Created By**

**Pragya Shukla**

---
