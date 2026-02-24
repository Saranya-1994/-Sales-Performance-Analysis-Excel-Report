# 📊 Sales Performance Analysis — Excel Report

A deep-dive Excel workbook analyzing global sales data across 100 orders, covering revenue, profit, regional performance, channel mix, and a short-term forecast.

---

## 📁 File

`Sales_Excel_Report_Deep.xlsx`

---

## 📋 Workbook Structure

The workbook contains **14 sheets**, organized as follows:

| Sheet | Description |
|---|---|
| `Dashboard` | Visual summary of the full report |
| `KPIs` | Top-level metrics: total revenue, profit, margin, and averages |
| `Insights` | Key analytical findings and observations |
| `Data_Cleaned` | Source dataset (100 orders) with region, country, item type, channel, dates, revenue, profit, and margin |
| `By_Item_Type` | Revenue, profit, and margin aggregated by product category |
| `By_Region` | Revenue, profit, and margin aggregated by geographic region |
| `By_Channel` | Online vs. Offline performance comparison |
| `Pareto_ItemType` | Pareto analysis — cumulative revenue/profit share by item type |
| `ItemType_Channel` | Cross-tab of revenue by item type and sales channel |
| `Monthly` | Monthly time series of revenue, profit, and margin (Jan 2010 – Jun 2017) |
| `Forecast` | 3-month revenue and profit forecast (Jul–Sep 2017) |
| `Outliers` | Top 10 orders by revenue with z-score flagging |
| `Charts` | Chart objects embedded in the workbook |
| `Sheet3` | Profit by region pivot summary |

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $137,348,768 |
| Total Profit | $44,168,198 |
| Overall Profit Margin | 32.2% |
| Avg Revenue / Order | $1,373,488 |
| Avg Profit / Order | $441,682 |
| Total Orders | 100 |

---

## 🔍 Key Insights

- **Top 3 item types** (Cosmetics, Office Supplies, Household) account for **70.7% of revenue** and **63.2% of profit**
- **Top 5 item types** drive **83.9% of total revenue**
- **Channel split** is 50/50 Online vs. Offline by order count, though revenue varies by item type
- **24 of 90 months** (26.7%) show zero revenue — seasonality analysis should treat the dataset as potentially incomplete

---

## 🗂️ Data Fields (Data_Cleaned Sheet)

| Field | Description |
|---|---|
| `Region` | Geographic region |
| `Country` | Country of the order |
| `Item_Type` | Product category |
| `Sales_Channel` | Online or Offline |
| `Order_Priority` | Priority code (H, M, L, C) |
| `Ship_Date` | Shipping date |
| `Unit_Cost` | Cost per unit |
| `Total_Revenue` | Total order revenue |
| `Total_Profit` | Total order profit |
| `Profit_Margin` | Profit as a fraction of revenue |
| `Expense` | Total cost (Revenue − Profit) |

---

## 🛠️ Requirements

- Microsoft Excel 2016+ or compatible spreadsheet software (e.g., LibreOffice Calc)
- Some sheets use slicers which require Excel for full interactivity

---

## 📌 Notes

- The forecast (Jul–Sep 2017) uses a trailing average margin assumption of **34.9%**
- Outliers are identified using z-scores on `Total_Revenue`; orders with z > 2 are flagged
- All monetary values are in **USD**
