## 📌 Overview

The PhonePe Transaction Analytics Dashboard is an interactive Power BI project designed to monitor transaction performance, payment success rates, customer demographics, and service-wise transaction trends.

This dashboard transforms raw transaction data into actionable business insights, enabling better decision-making through interactive visualizations and KPI tracking.

# 🎯 Business Objectives

- Analyze transaction volume and value.
- Monitor payment success rates.
- Track user engagement and growth.
- Understand customer demographics.
- Compare weekday and weekend transaction patterns.
- Identify top users and service categories.
- Generate actionable business insights.

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|--------|
| Total Transactions | 300K |
| Total Transaction Value | ₹3.47 Billion |
| Unique Users | 108K |
| Success Rate | 96% |
| MoM Transaction Growth | 8.97% |
| MoM Value Growth | 8.98% |

# 📈 Dashboard Features

### Transaction Analysis
- Monthly Transaction Trend
- Transaction Volume Tracking
- Transaction Value Tracking

### Payment Status Monitoring
- Successful Transactions
- Failed Transactions
- Pending Transactions

### Customer Segmentation
- Gen Z
- Millennials
- Gen X
- Boomers

### Service Analysis
- Loans
- Insurance
- Money Transfer
- Recharge & Bills

### User Analysis
- Top 5 Users by Transaction Value

### Usage Analysis
- Weekday vs Weekend Transactions

### Interactive Filters
- Month Filter
- Payment Status Filter

---

# 🔍 Key Insights
✅ 96% success rate ensures reliable and seamless digital payments.
✅ 300K transactions and ₹3.47B value indicate strong growth.

# 🛠️ Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Excel
- Data Modeling
- Data Visualization
- GitHub

# 📊 Visualizations Used

- KPI Cards
- Area Chart
- Donut Chart
- Column Chart
- Bar Chart
- Slicers
- Interactive Filters

---

# 🧮 DAX Measures

```DAX
Total Transactions =
COUNT(Transactions[Transaction_ID])

Total Value =
SUM(Transactions[Transaction_Value])

Unique Users =
DISTINCTCOUNT(Transactions[User_ID])

Successful Transactions =
CALCULATE(
    [Total Transactions],
    Transactions[Payment_Status] = "Successful"
)

Success Rate =
DIVIDE(
    [Successful Transactions],
    [Total Transactions]
)
```
# 📂 Repository Structure

PhonePe-Transaction-Dashboard/
│
├── PhonePe Dashboard.pbix
├── Dataset.xlsx
├── README.md
└── Screenshot 2026-06-21 140509.png

---

# 🚀 How to Use

1. Download the `.pbix` file.
2. Open using Power BI Desktop.
3. Refresh data if required.
4. Explore dashboard insights using filters and slicers.

---

---

# 📸 Dashboard Preview
![PhonePe Dashboard](https://raw.githubusercontent.com/vsaur557/Phonepe-Analysis-Dashboard-/main/Screenshot%202026-06-21%20140509.png)
