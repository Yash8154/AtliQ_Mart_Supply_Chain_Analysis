# 📦 AtliQ Mart – Supply Chain Performance Dashboard (Power BI)

This project is part of the Codebasics Resume Project Challenge (Oct 2023). It showcases my end-to-end skills in data analysis, storytelling with visuals, and dashboard design — focused on solving a real-world **supply chain issue** at AtliQ Mart, a growing FMCG brand in India.

🟢 **Live Dashboard**: Coming soon  
🎥 **Demo Video**: Optional  
📂 **Data Folder**: [View Raw Files](./data/)

---

## 🧠 Problem Statement

AtliQ Mart is a Gujarat-based FMCG company operating in **Surat, Ahmedabad, and Vadodara**, aiming to expand into Tier 1 cities. However, multiple **key customers didn’t renew contracts** due to poor delivery service.

> Management suspects two root issues:
> - Orders not being delivered **on time**
> - Orders not being delivered **in full**

The supply chain analytics team was tasked to **track daily service performance** using 3 core metrics:

- 📍 **OT%**: On-time delivery
- 📍 **IF%**: In-full delivery
- 📍 **OTIF%**: Orders delivered both on time and in full

The goal is to spot issues quickly and **prevent further customer churn** before expanding operations.

---

## 🎯 Project Goals

As the analyst (roleplay: **Peter Pandey**), I was tasked to:

- Design a **KPI dashboard** using stakeholder inputs
- Track delivery metrics across cities, customers, and products
- Compare **actual performance vs target**
- Highlight underperformance visually and provide insights

---

## 📊 Metrics Tracked

| KPI     | Description |
|---------|-------------|
| **OT%** | Orders delivered on or before the agreed date |
| **IF%** | Orders delivered with complete quantity |
| **OTIF%** | Orders delivered both on time and in full |
| **LIFR%** | Line Item Fill Rate |
| **VOFR%** | Volume Fill Rate |
| **ADOD** | Average Days of Delivery Delay |

---

## 🛠️ Tools & Techniques

- **Power BI**: Card visuals, Matrix, Sparklines, Conditional formatting
- **DAX**: Custom measures for OT, IF, OTIF, ADOD
- **Bookmarks**: Toggle between KPIs (OT%, IF%, OTIF%)
- **Data Modeling**: Fact & Dimension schema with clean joins
- **Storytelling**: KPI tracking → breakdown → trend → root cause view

---

## 📸 Dashboard Overview

<img src="./dashboard.png" width="800">

---

## 🧾 Data Model

<img src="https://github.com/YOUR_USERNAME/AtliQ_Mart_Supply_Chain_Analysis/blob/main/resources/data_model.png" height="400">

---

## 🔍 Key Insights

- ⚠️ **OT%, IF%, and OTIF% are consistently below target** across all 3 cities
- 📉 Average order delay is **1.69 days** beyond the agreed delivery date
- 🧈 Ghee, butter, and curd are among the **most delayed product categories**
- 📦 Customers like **Coolblue, Lotus Mart** consistently underperform on OTIF%
- 🟡 No visible **upward trend** in any KPI over the past few months
- 📊 **City-level charts** highlight Vadodara with the **worst OT%**

---

## 📁 Folder Structure

