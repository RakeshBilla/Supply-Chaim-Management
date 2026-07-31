# Supply Chaim Management
Supply Chain Management Dashboard project using Excel/Power BI, designed to track procurement, inventory, logistics, and sales performance. Features automated KPIs such as MTD/QTD/YTD Sales, Inventory Turnover, Fill Rate %, Backorder Rate, On‑Time Delivery %, Lead Time, Procurement & Transportation Costs, Forecast Accuracy, and Profitability analysis. Includes interactive dashboards with KPI cards, trend charts, and region/product breakdowns for actionable insights
# 📦 Supply Chain Management Dashboard

## 📖 Overview
This project delivers a comprehensive Supply Chain Management dashboard that tracks performance across **Orders, Inventory, Procurement, Logistics, and Demand Fulfillment**.  
The dashboard integrates multiple datasets and automates KPI calculations to provide actionable insights for optimizing operations, reducing costs, and improving customer satisfaction.

---

## 🎯 Key KPIs

### 1️⃣ Order & Sales KPIs
- **Total Orders** → `COUNT(Order_ID)`
- **Total Sales Revenue** → `SUM(Unit_Price * Quantity)`
- **Average Order Value (AOV)** → `SUM(Unit_Price * Quantity) / COUNT(Order_ID)`
- **Orders by Region/Country/City** → Geographic breakdown for insights

---

### 2️⃣ Inventory & Stock KPIs
- **Stock on Hand** → `SUM(Stock_On_Hand)`
- **Reorder Status** → % of products where `Stock_On_Hand < Reorder_Level`
- **Average Lead Time** → `AVG(Lead_Time_Days)`
- **Inventory Turnover Ratio** → `Total_Cost / Stock_On_Hand`

---

### 3️⃣ Procurement & Cost KPIs
- **Procurement Cost** → `SUM(Procurement_Cost)`
- **Transportation Cost** → `SUM(Transportation_Cost)`
- **Total Supply Chain Cost** → `SUM(Total_Cost)`
- **Cost per Unit** → `Total_Cost / SUM(Quantity)`

---

### 4️⃣ Logistics & Delivery KPIs
- **On-Time Delivery %** → % of orders where `Delivery_Status = "On-Time"`
- **Average Delay (days)** → `AVG(Delay_Days)`
- **Orders by Ship Mode** → Breakdown of Standard, Express, etc.
- **Transport Mode Utilization** → Orders per `Transport_Mode`

---

### 5️⃣ Demand & Fulfillment KPIs
- **Forecast Accuracy** → `1 - (ABS(Forecast_Demand - Actual_Demand) / Forecast_Demand)`
- **Fill Rate** → `AVG(Fill_Rate)` or `Fulfilled Quantity ÷ Demand`
- **Backorder Rate** → % of orders delayed due to insufficient stock
- **Demand vs Actual Sales Trend** → Forecast vs Actual Demand chart

---

## 🛠 Tech Stack
- **Excel** → PivotTables, advanced formulas, KPI calculations  
- **Power BI** → Data modeling, DAX measures, interactive dashboards  
- **SQL** → Data preparation, joins, aggregations  
- **Python (optional)** → Data cleaning and preprocessing  

---

## 🚀 Outcomes
