#  Cloud Kitchen — Sales & Inventory Dashboard

> An end-to-end data analysis project for a cloud kitchen operation: raw data cleaning, financial KPI calculations, and a fully designed Excel dashboard with 5 interactive charts.

---

## 📌 Project Overview

This project simulates a real-world business intelligence task for a cloud kitchen (ghost kitchen) business. Starting from raw daily operational data, the workflow covers data quality fixes, financial calculations, and executive-level reporting — all delivered inside a single polished Excel workbook.

---

## 🎯 Key Features

| Feature | Description |
|---|---|
| 🧹 Data Cleaning | Removed duplicate records; handled missing values using category-level statistical median |
| 💰 Financial Calculations | Computed Revenue, Total Cost, and Net Profit per product per day |
| 📊 5-Chart Dashboard | Line, clustered Bar, Pie, KPI Bar, and Waste Bar charts on a dark-themed dashboard sheet |
| 📋 Insights Report | Executive summary identifying top-performing products and operational waste |
| 🎨 Formatted Workbook | Dark-themed data sheet with color-coded KPI columns and auto-totals row |

---

## 📊 Dashboard Preview

### Charts Included
1. **Line Chart** — Daily net profit trend over time  
2. **Clustered Bar** — Produced qty vs. Sold qty per product (highlights overproduction)  
3. **Pie Chart** — Revenue share breakdown by product category  
4. **KPI Bar** — Total Revenue vs. Total Cost vs. Net Profit side-by-side  
5. **Waste Bar** — Unsold units per product (operational waste analysis)  

### KPI Cards (top of dashboard)
- 💰 Total Revenue
- 💸 Total Costs
- 📈 Net Profit
- ⚠️ Total Waste (units)

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** — Charts, formulas, conditional formatting, multi-sheet architecture  
- **Python 3** — Data processing pipeline  
- **Pandas** — Data cleaning, deduplication, missing value imputation  
- **OpenPyXL** — Programmatic workbook generation (styles, charts, layouts)  

---

## 📂 Repository Structure

```
cloud-kitchen-dashboard/
│
├── cloud_kitchen_dashboard.xlsx   # Final deliverable (cleaned data + dashboard)
├── build_dashboard.py             # Python script that generates the workbook
├── raw_data.xlsx                  # Original raw dataset (with duplicates & nulls)
└── README.md
```

---

## 🔍 Key Insights (from the Report)

- **Top Performer**: *Butter Croissant* — highest net profit driven by strong demand and healthy margin. Recommended for scaled production during peak hours.  
- **Highest Waste**: *Chocolate Mousse* — 40 out of 70 units went unsold. Production plan needs revision to align with actual demand.  
- **Data Quality Issues Found**:
  - Duplicate entry detected for *Chocolate Mousse (05-21)* → removed  
  - Missing sales value for *Pistachio Cake (05-22)* → imputed with category median  
- **Category Insight**: Bakery items dominate total revenue and should be prioritized in inventory management.

---

## 🚀 How to Use

1. Clone the repository  
   ```bash
   git clone https://github.com/YOUR_USERNAME/cloud-kitchen-dashboard.git
   ```
2. Install dependencies  
   ```bash
   pip install pandas openpyxl
   ```
3. Run the script to regenerate the workbook  
   ```bash
   python build_dashboard.py
   ```
4. Open `cloud_kitchen_dashboard.xlsx` in Excel or Google Sheets

---

## 💼 CV / Resume Description

> **Cloud Kitchen Sales & Inventory Dashboard** | *Excel · Python · Pandas · OpenPyXL*  
> Built an end-to-end data analysis pipeline for a cloud kitchen: cleaned raw operational data (deduplication, statistical imputation), engineered financial KPIs (revenue, cost, net profit), and designed a 5-chart executive dashboard with dark-themed formatting and an automated insights report.  
> 🔗 [github.com/YOUR_USERNAME/cloud-kitchen-dashboard]

---

## 👩‍💻 Author

**[Your Name]**  
Data Analyst | Excel · Python · Business Intelligence  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)
