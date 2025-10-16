# Zara-Analysis
# 📊 Zara Retail Sales – Power BI Dashboard Project

## 📂 Dataset
The dataset used in this project is uploaded in this repository.  

📌 [**Download Dataset (CSV)**](./zara_retail_sales.csv)

---

## 🛠️ Data Cleaning & Preparation
Steps performed during preprocessing:

- 🗑️ Parsed **semicolon-separated** fields into proper rows & columns  
- 🚫 Replaced **null values** with blank spaces  
- 📆 Extracted **Time, Day Name, Month Name** from `scraped_at` column  
- ➕ Added calculated columns: `Total Sales = Price × Sales Volume`, `Promotion Flag`, `Seasonal Flag`  
- 📋 Created a **Position Mapping Table** (Aisle, End-cap, Front of Store) with visibility & purpose  

---

## 📊 Analysis & Modeling
Power BI transformations + DAX measures used to create insights:

- 📈 **Sales Overview** (KPIs: Total Sales, Units Sold, Avg Price)  
- 🏬 **Position Impact** (Aisle vs End-cap vs Front of Store)  
- 🎯 **Promotion & Seasonal Contribution**  
- 🧥 **Product Performance** (Table + Conditional Formatting)  
- 📉 **Price vs Demand** (Scatter chart: Price vs Sales Volume)  

---

## 🖼️ Dashboard Pages
- **Page 1: Sales Overview** → KPIs, Position-wise sales, Promotion/Seasonal breakdown  
- **Page 2: Product Performance** → Table (Top/Bottom products), Scatter chart, Slicers  
- **Page 3: Seasonal Insights** → Seasonal vs Non-seasonal contribution, Category breakdown  

---

## 🔑 Key Insights
- 💰 **Total Sales** driven by a few top-performing jackets  
- 🏬 **End-cap placement** shows higher visibility & sales impact  
- 🎯 **Promoted products** contribute significantly to volume uplift  
- 🍂 **Seasonal products** form a major share in peak months  
- 📉 **Price sensitivity** visible: lower-priced items sell in higher volumes  

---

## ✅ Recommendations
- 🚀 Focus on **End-cap & Front of Store** placements for high-visibility products  
- 🎯 Run **targeted promotions** on mid-range products to boost sales  
- 🍂 Align **seasonal inventory** with demand peaks  
- 📊 Use dashboard insights for **pricing & display strategy**  

---

## 📂 Project Files
- `zara_retail_sales.csv` → Cleaned dataset  
- `Zara_Retail_Dashboard.pbix` → Full interactive Power BI dashboard  
- `Dashboard_Screenshots/` → Preview images  

---

## 🚀 Tech Stack
- **Power BI Desktop** → Data Modeling, Dashboarding  
- **Power Query (M)** → Data Cleaning & Transformation  
- **DAX** → Measures & KPIs  

---
