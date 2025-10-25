# 📊 Sales & Profit Performance Dashboard (Power BI)

### 🧭 A 4-page interactive business intelligence dashboard built in Power BI to analyze sales performance, profitability trends, and customer behavior across products, segments, and regions.

---

## 🧠 Project Overview

This project demonstrates the **end-to-end Business Intelligence workflow** — from data preparation and modeling to visualization and storytelling — designed to help business stakeholders make **data-driven decisions**.

The dashboard focuses on understanding:
- What are the **key drivers of profit**?
- How do **sales and margins** vary across time, categories, and customers?
- Which **regions and segments** deliver the highest value?

---

## 📋 Table of Contents

1. [Project Objective](#project-objective)
2. [Dashboard Pages](#dashboard-pages)
3. [Tools & Skills Used](#tools--skills-used)
4. [Data Model](#data-model)
5. [Key DAX Measures](#key-dax-measures)
6. [Key Insights](#key-insights)
7. [Design Approach](#design-approach)
8. [Outcomes](#outcomes)
9. [Dashboard Preview](#dashboard-preview)

---

## 🎯 Project Objective

To design an interactive Power BI dashboard that enables stakeholders to:
- Monitor overall **sales and profitability performance**  
- Track **monthly trends** in AOV (Average Order Value) and profit margins  
- Analyze **product and category-level contribution**  
- Evaluate **regional and customer segment performance**  
- Derive **strategic insights** for improving business efficiency  

---

## 📈 Dashboard Pages

### 🧾 **1. Executive Summary**
- Displays overall business KPIs: Total Sales, Profit, AOV, and Profit Margin %.  
- Includes YoY comparison cards and quick performance highlights.  
- Provides a high-level overview of company performance.

---

### 📦 **2. Category & Product Analysis**
- Breaks down profitability and contribution by product categories and sub-categories.  
- Identifies top-performing products and underperforming ones.  
- Helps in product-level decision-making and inventory prioritization.

---

### 📉 **3. Sales & Profit Trends**
- Analyzes monthly sales and profit movements.  
- Tracks AOV and Profit Margin % trends to detect pricing or efficiency changes.  
- Segment-wise profit comparison to reveal customer behavior differences.

---

### 🌍 **4. Customer & Regional Performance**
- Region-wise sales and profit visualization (map view).  
- Customer segment performance trends and top 10 profit-generating cities.  
- Highlights areas for growth, regional efficiency, and expansion opportunities.

---

## 🧰 Tools & Skills Used

| Category | Tools / Concepts |
|-----------|------------------|
| **Data Visualization** | Power BI |
| **Data Preparation** | Power Query (ETL) |
| **Data Analysis** | DAX (Data Analysis Expressions) |
| **Data Cleaning** | Microsoft Excel |
| **Design Principles** | Minimalist corporate theme (Navy, Teal, Gray) |

---

## 🧩 Data Model

- **Fact Table:** Sales (contains sales, profit, discount, quantity, order date, etc.)  
- **Dimension Tables:** Products, Categories, Customers, Regions, Dates  
- Relationships built using **Star Schema** design for optimized querying and reporting.

---

## 🧮 Key DAX Measures

| Measure | Formula | Purpose |
|----------|----------|----------|
| **Profit Margin %** | `DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales]), 0)` | Measures profitability ratio |
| **AOV (Average Order Value)** | `DIVIDE(SUM(Sales[Sales]), COUNT(Sales[Order ID]))` | Calculates average order value |
| **YoY Sales Growth %** | `DIVIDE(SUM(Sales[Sales]) - CALCULATE(SUM(Sales[Sales]), DATEADD(Calendar[Date], -1, YEAR)), CALCULATE(SUM(Sales[Sales]), DATEADD(Calendar[Date], -1, YEAR)))` | Tracks year-over-year growth |
| **Total Profit** | `SUM(Sales[Profit])` | Total company profit |
| **Total Sales** | `SUM(Sales[Sales])` | Total company sales |

---

## 💡 Key Insights

📍 **Overall:**  
- Profit margins declined slightly despite steady sales — indicating possible cost or discount pressures.  
- AOV fell 8% YoY, showing smaller average order sizes.  

📍 **Segment Analysis:**  
- Consumer segment dominated total profit, while Corporate improved margin efficiency.  
- Home Office segment underperformed, suggesting potential cost inefficiency.  

📍 **Category Insights:**  
- Technology and Furniture categories generated the highest profit.  
- Certain product lines showed high sales but low margins, highlighting optimization opportunities.  

📍 **Regional Insights:**  
- North America remains the top sales region, while Europe leads in profit margin %.  
- Top-performing cities (New York, Los Angeles) contribute majority of total profit.

---

## 🎨 Design Approach

- **Theme:** Minimalist corporate — clean white background, teal/navy accents, consistent KPI formatting.  
- **Font:** Segoe UI for clarity and professionalism.  
- **Visual Types:** Line charts, bar charts, KPI cards, maps, and trend visuals.  
- **Layout Flow:** Storytelling approach — from Overview → Trends → Products → Regions.  
- **Interactivity:** Filters for Month, Category, and Segment.

---

## 🏁 Outcomes

This Power BI project demonstrates:
- Ability to build **multi-page, insight-driven dashboards**.  
- Proficiency in **data modeling, DAX, and business storytelling.**  
- Understanding of **real-world KPIs** for sales, profitability, and customer segmentation.  

It mirrors the workflow of a **Business Intelligence Analyst**, bridging data analytics and strategic insight generation.

---

## 🖼️ Dashboard Preview 
- Page 1: Executive Summary 
![alt text](image.png) 
- Page 2: Category & Product Analysis
![alt text](image-1.png) 
- Page 3: Sales & Profit Trends  
![alt text](image-2.png)
- Page 4: Customer & Regional Performance  
![alt text](image-3.png)
---

## 👩‍💼 Author

**Prisha Prakash**  
Business Analyst | Power BI Developer | Data Storyteller  
📫 prishaprakash9903@gmail.com 

---

