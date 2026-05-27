# Blinkitt-sales-analysis

# Blinkit Quick Commerce Sales Analytics Dashboard | Power BI

### 📌 Problem Statement
Analyzed Blinkit grocery sales data worth $1.2M to identify revenue drivers, outlet performance, and category trends for optimizing quick-commerce strategy.

### 🛠️ Tools Used
- **Power BI:** Data visualization, DAX, Slicers, Donut/Bar/Area Charts
- **Excel:** Data cleaning, KPI calculation  
- **Domain:** Quick Commerce, Retail Analytics, Sales KPIs

### 📊 Key Metrics & Insights

#### **KPI Summary**
| Metric | Value | Business Meaning |
| --- | --- | --- |
| Total Sales | $1.2M | Overall platform GMV |
| Average Sale | $141 | AOV per order – healthy for grocery |
| Items Sold | 12.2K | Total units delivered |
| Avg Rating | 500K | *Data anomaly – should be 4.5/5 scale* |

#### **Critical Business Insights**
1. **Outlet Performance:** Supermarket Type1 drives 65% of total sales  
   → **Action:** Expand Type1 outlets. Audit Type2/Type3 for low 11% share.

2. **Category Trends:** Fruits & Vegetables + Snack Foods are top categories  
   → **Action:** Ensure 10-min delivery SLA for perishables. Bundle snacks for AOV boost.

3. **City Tier Analysis:** Tier 1 & Tier 3 cities equal at $472K sales, Tier 2 lags at $393K  
   → **Action:** Tier 2 needs marketing push. Tier 3 performing above expectation.

4. **Yearly Trend:** Sales peaked in 2018, declined post-2020  
   → **Action:** Investigate 2020 dip – COVID impact or competition from Zepto/Instamart.

5. **AOV Insight:** $141 AOV is strong for grocery. Quick commerce avg = $80-100  
   → **Action:** Indicates bulk ordering behavior. Promote ‘Weekly Basket’ feature.

### 🎯 Recommendations for Blinkit Ops Team
1. **For Type1 Outlets:** Double dark store count – they deliver 6x more than others.
2. **For Tier 2 Cities:** Run ‘Free Delivery’ campaign to close $79K gap vs Tier 1.
3. **For 2018-2022 Decline:** Relaunch loyalty program to recover lost 2018 peak.
4. **For Categories:** Stock 2x inventory for Fruits/Veg during 6-9 PM peak hours.

### ⚠️ Data Quality Observations
Identified 2 issues showing attention to detail:
1. `AVG RATING = 500K` is incorrect. Should be 4-5 scale. Needs data validation.
2. Two charts titled 'Sum of Rating by Outlet Type' but show sales data – label mismatch.
3. Total sales $1.2M vs bar chart max 200K – time aggregation difference noted.

### 📂 Files in Repo
1. `blinkit_sales_data.csv` – Sample dataset
2. `blinkit_dashboard.pbix` – Power BI file with filters
3. `dashboard.png` – Screenshot for recruiters
4. `DAX_Measures.txt` – AOV, YoY Growth formulas

### 🎯 Skills for TCS/HCL/Infosys/Blinkit Analytics Roles
Quick Commerce KPIs, Outlet Analysis, Category Management, DAX, Power BI, Data Quality Audit, GMV Tracking, Business Storytelling

---
**Connect:** [Your LinkedIn] | **Note:** Project built on sample data to demonstrate retail analytics skills for IT services & startup roles.
