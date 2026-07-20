# 🏭 Manufacturing Sales Dashboard — Power BI

An interactive 3-page Power BI dashboard analyzing manufacturing sales data with MySQL as the data source. Built to provide actionable insights across revenue, product performance, and regional targets.

---

## 📊 Dashboard Pages

### Page 1 — Sales Overview
- Total Revenue, Total Orders, Total Quantity, Revenue After Discount KPI Cards
- Monthly Revenue Trend (Line Chart)
- Top 5 Customers by Revenue (Bar Chart)
- Revenue by Category (Pie Chart)
- MOM Growth % and YTD Revenue Cards
- Date Slicer for dynamic filtering

### Page 2 — Product Analysis
- Product-wise Revenue Bar Chart
- Category-wise Average Order Value
- Product Matrix Table (Revenue + Quantity)

### Page 3 — Regional Performance
- Revenue by Region (Bar Chart)
- Target vs Actual Gauge
- Region-wise Customer Table
- Region Slicer

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard Development |
| MySQL | Data Source & SQL Queries |
| DAX | Custom Measures & KPIs |
| Data Modeling | Table Relationships |

---

## 📐 DAX Measures Built

```
1. Total Revenue
2. Total Orders
3. Revenue After Discount
4. Total Quantity
5. MOM Growth %
6. YTD Revenue
7. Target vs Actual %
8. Avg Order Value
```

---

## 🗄️ Database Schema

```sql
manufacturing_sales
├── Products     (product_id, product_name, category, unit_price)
├── Customers    (customer_id, customer_name, region, city)
├── Sales        (sale_id, sale_date, customer_id, product_id, quantity, discount)
└── Targets      (target_id, region, month, target_amount)
```

---

## ✨ Key Features

- ✅ Custom Tooltip Pages — contextual KPIs on hover
- ✅ Drillthrough Navigation — category-level deep dive
- ✅ Dynamic Date Slicer — filter by date range
- ✅ Region Slicer — filter by North / South / West
- ✅ Target vs Actual Gauge — performance tracking
- ✅ MOM Growth — month over month trend analysis
- ✅ YTD Revenue — year to date tracking

---

## 📈 Key Insights

- Total Revenue: ₹4.1L across 15 transactions
- Machine Parts contributes **40.33%** of total revenue
- **Rane Group** is the top customer (₹78K revenue)
- May month shows seasonal dip in revenue trend
- North region drives highest order volume

---

---

## 👩‍💻 Author

**Saravanan C (Sara)**
- MCA Graduate | Data Analyst
- GitHub: [github.com/Saravana999](https://github.com/Saravana999)
- Skills: Power BI | MySQL | Python | SQL | DAX

---

## 📌 Related Projects

- [Indian Bank Credit Risk Analysis Dashboard](#)
- [Financial Performance Dashboard](#)
- [Digital Banking Dashboard](#)
