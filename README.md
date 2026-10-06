# bakery-sales-dashboard
"Interactive Excel dashboard analyzing 20K+ bakery transactions"
# 🥐 Bakery Sales Dashboard

An interactive Excel dashboard analyzing 20,500+ point-of-sale transactions from a bakery, covering October 2016 to April 2017. Built entirely with pivot tables, pivot charts, and slicers — no macros, no external tools.

## 📊 Overview

The raw dataset contained only transaction IDs, item names, and timestamps — no price or revenue data. So instead of a revenue-focused dashboard, this project analyzes **volume, timing, and customer behavior patterns**: what sells, when people buy, and how weekday vs. weekend habits differ.

## 🔍 Key Insights

- **Coffee dominates** — consistently the top seller across every filter, at roughly 30%+ share of total items sold.
- **Weekdays outsell weekends** in absolute volume: 12,807 vs. 7,700 items sold.
- **Afternoon is the real rush period** (11,569 items) — not morning (8,404), which is a common assumption for bakeries.
- **Rush-hour volume climbs through the morning** and plateaus toward midday.
- **November, February, and March** were the strongest months in the dataset.

## 🛠️ Built With

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers (for interactive cross-filtering)
- Helper columns (Hour, Month extraction from timestamps)

## 📸 Screenshots

### Full Dashboard View
![Dashboard Overview](screenshots/dashboard-overview.png)

### Filtered by Weekday
![Slicer Filtered View](screenshots/slicer-filtered-view.png)

## 📁 Files

- `bakery_sales_dashboard.xlsx` — the full interactive dashboard
- `screenshots/` — static previews of the dashboard in different filter states

## 💡 What This Project Demonstrates

- Structuring raw transactional data into clean pivot-table-ready format
- Designing multi-chart dashboards with synchronized slicers
- Translating "what sells" into "what the business should actually do" (staffing, promotions, inventory timing)
- Iterating on chart design for clarity (e.g., simplifying an overcrowded pie chart into a readable bar chart)

## 📬 Contact

**Gul Andam**
Freelance Data Analyst | Excel & Power BI
Fiverr: gul_andam_8
