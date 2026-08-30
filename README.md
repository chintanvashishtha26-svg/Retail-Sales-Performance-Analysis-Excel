# Retail-Sales-Performance-Analysis-Excel
Interactive Excel Dashboard analyzing 500k+ transactional e-commerce records.
#  Retail Sales Analytics & Interactive Executive Dashboard

An end-to-end data analytics project built using **Microsoft Excel**. This project transforms over 500,000 raw e-commerce transaction records into an interactive executive dashboard delivering actionable business insights on sales trends, market geography, and customer purchasing behavior.

---

## 📌 Dashboard Preview
![Retail Sales Dashboard](dashboard.png)

---

## 📥 Project Dataset & Workbook
Due to file size limits for 500K+ transactional records, the complete dynamic workbook is hosted on Google Drive:
- **Download Full Interactive Excel Workbook (.xlsx):** [Click here to Access Workbook](https://drive.google.com/file/d/1LX_lg2uCAtIxW7NtLd_SWchTKfhIA66W/view?usp=drive_link)

---

## 🛠️ Key Features & Methodology

### 1. Data Cleaning & Feature Engineering
- Processed raw transactional data, verifying integrity across quantities, unit prices, and timestamps.
- Engineered calculated fields to support time-series and demographic analysis:
  - `Total Sales`: Derived via `[Quantity] * [UnitPrice]`
  - `Invoice Month`: Extracted Year-Month format (`=TEXT(Date, "yyyy-mm")`)
  - `Days of Week`: Extracted day names (`=TEXT(Date, "dddd")`)

### 2. Multi-Dimensional Data Aggregation (Pivot Tables)
- **Monthly Revenue Trajectory:** Evaluated month-over-month revenue trends.
- **Top 10 International Markets:** Aggregated regional sales to highlight key revenue drivers.
- **Weekly Sales Velocity:** Evaluated order patterns across days of the week.

### 3. Executive Dashboard Design & Interactivity
- **KPI Summary Cards:** Dynamic visibility into Total Revenue, Primary Market, and Peak Sales Day.
- **Interactive Slicers:** Implemented multi-pivot connected slicers for `Country` and `Days of Week` enabling exploratory filtering.
- **Clean UI:** Standardized 2-D visual aesthetics (Line, Clustered Bar, Column) without cluttered gridlines.

---

## 💡 Key Business Insights
1. **Market Concentration:** The United Kingdom accounts for the dominant share (>85%) of total revenue, followed by key European markets like Netherlands, EIRE, and Germany.
2. **Purchasing Velocity:** Order frequency peaks significantly on **Thursday**, while Sunday registers lower transaction volume.
3. **Seasonal Spikes:** Late Q3 and Q4 exhibit major sales acceleration, aligning with holiday season purchasing behavior.

---

## 💻 Tech Stack
- **Tool:** Microsoft Excel (Advanced)
- **Techniques:** Data Modeling, Structured Table Formulas, Pivot Tables, Pivot Charts, Slicers, KPI Card Design
-
