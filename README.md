# MavenMarket_Business_Insights  

📊 **Power BI Dashboard analyzing sales performance, profitability, and return rates across North American retail regions using Maven Market’s 1997–1998 dataset.**

---

## 🧩 Overview  
This project explores **Maven Market’s regional sales and profitability performance** through an interactive Power BI dashboard.  
It simulates a real-world retail analytics workflow — transforming raw transactional data into clean, business-ready insights.  

---

## ⚙️ Data Model  
The dataset follows a **star schema** with lookup tables for **Products, Customers, Stores, Regions, and Calendar**.  
Returns and transactions are modeled as fact tables to support profitability and return-rate analysis.  

📘 *Schema Type:* Star schema with a small snowflake structure for Regions → Stores  

![Data Model](https://github.com/Axel-Rodz/MavenMarket_Business_Insights/blob/main/Model%20Screenshot/DataModel.png)

---

## 📊 Dashboard Highlights  
- **KPI Cards** — Tracks monthly transactions, profits, and return rates against goals  
- **Regional Map** — Visualizes performance across USA, Canada, and Mexico  
- **Brand Profit Matrix** — Compares total profit, margin %, and return rates per brand  
- **Monthly Revenue Trend** — Displays seasonal patterns in 1997–1998  
- **Treemap Visualization** — Shows proportional revenue and returns by country  

![Executive Dashboard](https://github.com/Axel-Rodz/MavenMarket_Business_Insights/blob/main/Exec%20Dashboard/ExecDash.png)

---

## 🧮 Key Metrics  
- Current Month Transactions  
- Current Month Profit  
- Current Month Returns  
- Profit Margin %  
- Return Rate %  
- Total Revenue vs Target Revenue  

---

## 🧠 Insights  
- Profit margins average **~59%–61%**, showing strong brand pricing.  
- **Return rates stay under 1.2%**, suggesting product reliability.  
- **USA** and **Mexico** drive most transactions and profit.  
- Seasonal lift appears in Q4, consistent with holiday demand.  

---

## 🧰 Tools & Techniques  
- **Power BI Desktop** for dashboarding  
- **Power Query** for data transformation  
- **DAX** for advanced metrics and KPIs  
- **Maven Market Dataset (1997–1998)**  

---

## 🚀 Future Enhancements  
- Add YoY and MoM trend cards  
- Build Customer Segmentation and Cohort dashboards  
- Integrate forecasting or “Goal Seek” price modeling  

