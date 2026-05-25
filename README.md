# ☕ Coffee Sales Dashboard — Power BI Project

> An end-to-end interactive Power BI dashboard analyzing coffee shop sales across multiple store locations, product categories, and time periods — built with advanced Power BI features including Drillthrough, Tooltip Pages, Dynamic Title, Slicers, and DAX measures.
---
## 📸 Dashboard Preview

### Sales Dashboard (Main Page)

<img width="1326" height="786" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/c90470a9-eb36-491e-86c0-92a393497f2d" />


### Category Deep Dive (Drillthrough Page)

<img width="1331" height="792" alt="Category Analysis" src="https://github.com/user-attachments/assets/a2223a51-5430-4da4-b4b7-246e8b5a0092" />


---
## 📌 Project Overview

This Power BI report provides a comprehensive view of sales performance for a multi-location coffee shop chain. It covers 6 months of transaction data (January – June 2023) across three stores — **Tampa**, **Miami**, and **Orlando** — and tracks sales across five product categories.

Built as a first Power BI project, this report demonstrates end-to-end BI development: data modeling, DAX calculations, interactive visuals, drillthrough pages, and tooltip pages.

---

## 🏪 Business Context

| Detail | Value |
|---|---|
| Stores | Tampa, Miami, Orlando |
| Time Period | Jan 2023 – Jun 2023 |
| Product Categories | Coffee, Tea, Bakery, Drinking Chocolate, Coffee Beans |
| Total Sales | ₹ 698.81K |
| Total Transactions | 149K |
| Total Quantity | 214K |
| Avg Order Value | $4.69 |

---

## 📄 Report Pages

### 1. Sales Dashboard *(Main Page)*
The home page gives an executive-level summary of performance across all stores and categories.

**Visuals included:**
- KPI Cards — Total Sales, Total Transactions, Total Quantity, Avg Order Value
- Monthly Sales Trend (Line Chart)
- Sales by Store Location (Donut Chart)
- Sales by Product Category (Bar Chart)
- Sales & Transactions by Hour of Day (Line Chart)
- Slicers — Category, Location, Month
- Key Insights banner (static highlights)

---

### 2. Category Analysis *(Drillthrough Page)*
Accessible by right-clicking a store from the main dashboard. Provides a deep dive into category-level performance for the selected store.

**Visuals included:**
- KPI Cards — Total Sales, Total Transactions, Avg Order Value, MoM Growth %
- Sales Trend with MoM % labels (Combo Bar + Line Chart)
- Current vs Last 90 Days Sales (Donut Chart)
- Weekend vs Weekday Sales Analysis (Bar Chart)
- Store Sales Ranking by Category (Table with data bars)
- Month slicer panel

---

### 3. TT Sales by Location *(Tooltip Page)*
A compact tooltip that appears when hovering over store-related visuals. Shows a quick location-level sales breakdown.

---

### 4. TT Sales by PC *(Tooltip Page)*
Tooltip showing product category breakdown on hover — useful for quick category comparisons without leaving the current page.

---

### 5. TT Sales by PT *(Tooltip Page)*
Tooltip focused on time-based sales patterns, giving context on peak hours when hovering over time-series visuals.

---

## 🔑 Key Insights

- 📈 **Sales peak between 8 AM – 10 AM** across all locations
- ☕ **Coffee & Tea together contribute ~67%** of total sales
- 🏆 **Tampa leads** all three stores in total sales contribution (236.51K — 33.8%)
- 📅 **Weekday sales (170K) outperform weekend sales (66K)** significantly
- 📊 **June recorded the highest monthly sales** at 166K, showing consistent month-over-month growth

---

## 🗂️ Data Model

The report is built on a star schema with:

- **Fact Table** — Transactions (sales amount, quantity, transaction ID, datetime)
- **Dimension Tables** — Date, Store Location, Product Category, Product

Relationships are set up to allow cross-filtering across all visuals by store, category, and time.

---

## ⚙️ Features Used

| Feature | Details |
|---|---|
| Drillthrough | Category Analysis page (filter by store) |
| Tooltip Pages | 3 custom tooltip pages for contextual hover info |
| Slicers | Category, Location, Month across pages |
| DAX Measures | MoM Growth %, Last 90 Days Sales, Grand Total %, Rankings |
| Conditional Formatting | Data bars on category ranking table |
| Dynamic Titles | Page titles update based on slicer selection |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
- **Power BI Desktop** — Report development
- **Power Query (M)** — Data transformation and cleaning
- **DAX** — Calculated measures and KPIs
- **Data Source** — CSV / Excel transactional data

---


## 📁 Project Structure

```
coffee-sales-powerbi
│
├── Coffee_Sales_Dashboard.pbix         # Main Power BI report file
├── README.md                           # Project documentation
├── Sales dashboard.png                  # Screenshot — Sales Dashboard
└── category Analysis.png              # Screenshot — Category Analysis
```

---

> 💡 **Tip:** Right-click any store or category data point on the main dashboard → Select **Drill through → Category Analysis** to navigate to the deep-dive page with filters automatically applied.

---

## 🚀 How to Use

### Prerequisites
- **Power BI Desktop** (free) — [Download here](https://powerbi.microsoft.com/desktop/)

### Steps

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/coffee-sales-powerbi.git
   ```

2. **Open the file** — double-click `Coffee_Sales_Dashboard.pbix` or open via Power BI Desktop → File → Open

3. **Explore the dashboard:**
   - Use the **dropdown slicers** (Category / Location / Month) to filter
   - Click **store name buttons** on the left panel to filter by location
   - **Right-click** any data point → Drill through → Category Analysis
   - **Hover** over store or category visuals to see custom tooltip pages
   - Use the **back button** (top-left on drillthrough pages) to return

4. **Switch pages** using the tabs at the bottom: Sales Dashboard → Category Analysis → TT Sales by Location → TT Sales by PC

---



## 🌱 What I Learned 

Building this dashboard taught me:

- How to design a **multi-page report** with a clear user journey
- Creating **drillthrough pages** for contextual deep-dives
- Building **custom tooltip pages** to add hover context
- Writing **DAX measures** for MOM growth, rolling periods, and GT%
- Setting up a proper **Date table** and marking it correctly
- Using **conditional formatting** in tables to highlight performance
- Designing with **consistent color themes** (coffee brown palette 🟤)
- The difference between **report-level**, **page-level**, and **visual-level** filters

---

## 👩‍💻 About the Author

**Shalini Saha**  
*Data Analyst | Power BI | Excel | SQL*

💬 Passionate about transforming raw HR data into meaningful workforce insights  
🔗 [LinkedIn](https://www.linkedin.com/in/shalini-saha-b127b428b/) | [GitHub](https://github.com/ShaliniSaha97/)


---

## ⭐ If you found this helpful

Give this repo a ⭐ star — it helps others find it and motivates me to keep building!

---

*Built with ❤️ and lots of ☕*



