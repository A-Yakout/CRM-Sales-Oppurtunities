# 📊 CRM Sales Opportunities Dashboard

## 🧩 Project Overview
This project analyzes a **B2B sales pipeline** for a company selling **computer hardware**.  
Using the CRM Sales Opportunities dataset from [Maven Analytics](https://mavenanalytics.io/data-playground/crm-sales-opportunities), the goal was to explore and visualize the company’s performance across products, regions, and sales teams.

The dashboard was built in **Excel** using **Power Query**, **Pivot Tables**, and **Interactive Charts** to uncover trends and insights that can help management make data-driven decisions.

---

## ⚙️ Tools Used
- **Microsoft Excel**
  - Power Query (Data Cleaning & Transformation)
  - Pivot Tables (Data Aggregation)
  - Slicers & Charts (Visualization)
- **Power BI** *(optional for future integration)*

---

## 🧹 Data Preparation (Power Query)
Performed key data cleaning and transformation steps:
- Removed duplicates and null values.
- Extracted **Year, Quarter, and Month** from the date column.
- Created new calculated columns:
  - `Deal_Value` = Quantity × Unit Price
  - `Win_Rate` = Opportunities Won ÷ Total Opportunities
  - `Profit` = Deal_Value × Profit_Margin
- Standardized regional and category names for consistency.
- Categorized sales stages: **Prospecting**, **Engaging**, **Lost**, **Won**.

---

## ❓ Business Questions Answered
The analysis answers critical management questions such as:
- Which **products** generate the highest sales revenue?
- How do **sales vary across regions** (East, West, Central)?
- What are the **quarterly sales trends** throughout the year?
- Who are the **top-performing sales agents**?
- What percentage of opportunities were **won vs lost**?
- Which **deal stages** have the most opportunities stuck?
- How does **profit distribution** differ by product and region?

---

## 📈 Dashboard Insights
The interactive Excel dashboard provides:
- **Top Selling Products** by total revenue.
- **Sales by Region** to identify top-performing markets.
- **Sales by Quarter** for trend analysis.
- **Opportunities by Deal Stage** showing progress in the sales funnel.
- **Top Sales Agents** ranked by closed deal value.
- **Won vs Lost % Donut Chart** to visualize success rates.
- **Dynamic Filters (Slicers)** for Quarter, Region, and Deal Stage.

---

## 🧠 Key Insights
- The **GTXPro** series led in total revenue among all product lines.
- **Q2** recorded the highest quarterly sales, indicating strong seasonal demand.
- The **West region** contributed the largest share of total sales.
- **Darcel Schlecht** emerged as the top-performing sales agent with the highest deal value.
- **60% of opportunities were won**, showing strong overall performance.

---

## 🚀 Future Improvements
- Automate data refresh with Power Query connections.
- Integrate with **Power BI** for advanced visualization and storytelling.
- Add **VBA automation** for report generation and trend alerts.
- Include **predictive analysis** for upcoming sales using ML models.

---

## 📷 Dashboard Preview
![CRM Sales Dashboard](./CRM%20Dashboard%20modified.png)

---

## 👨‍💻 Author
**Eng. Abdelrahman Yakout**  
Data Analyst | Excel & VBA Developer  
📧 Email: [abdelrhmanmohamedyakout.com]  
🔗 LinkedIn: [linkedin.com/in/a-yakout]  
📍 Location: Egypt  

---

> This project demonstrates how Excel and Power Query can turn raw sales data into actionable business insights through automation and interactive visualization.
