# 📊 Product & Category Performance Dashboard (Excel)

**Which product categories actually make money, and which ones just look busy?**
I built this interactive Excel dashboard to answer that question using 2,707 sales transactions across 17 countries.

![Dashboard preview](images/dashboard.png)

---

## 🎯 The Business Problem

A multi-category outdoor and lifestyle retailer sells through four channels in four European regions. Leadership can see total sales, but not:

- Which categories and products drive **profit**, not just revenue
- How **discounting** is affecting margins
- Which **channels and customer types** matter most
- When demand peaks during the year

This dashboard puts all of that on one screen, with filters so anyone can drill down without touching a formula.

---

## 🔢 Headline Numbers

| Metric | Value |
|---|---|
| Total Revenue | $645,223 |
| Total Profit | $296,384 |
| Gross Profit Margin | 45.94% |
| Units Sold | 6,698 |
| COGS | $348,839 |
| Total Discount Given | $44,734 |

---

## 💡 Key Insights

1. **Camping is the biggest category but not the most profitable per dollar.** It brings in about $198.5K (the largest share of revenue) at a 42.8% margin, the lowest of the five.
2. **Fitness is the opposite.** It is the smallest category by revenue ($55.6K) but has the best margin at 51.2%. Cycling (48.9%) and Travel (47.7%) also beat the overall average.
3. **Online Store is the strongest channel.** It generates roughly 40% of revenue, followed by Corporate at about 28%. Marketplace is the weakest at about 14%.
4. **Demand is seasonal.** Revenue peaks in **June** and again in **November** across most categories, and Q1 is the weakest quarter by a clear gap.
5. **Customer mix is balanced.** Business, New and Returning customers each contribute roughly a third of revenue, so growth does not depend on a single segment.
6. **Revenue is concentrated in Western and Central Europe**, which together account for about 60% of sales.

## ✅ What I'd Recommend

- Protect margin in **Camping** by reviewing discount depth, since volume is already strong there.
- Test more promotion and shelf space for **Fitness and Cycling**, where each sale earns more.
- Plan inventory and campaigns around the **June and November** peaks, and look for ways to lift Q1.

---

## 🛠️ What's Inside the Workbook

| Sheet | Purpose |
|---|---|
| **Data** | Cleaned transaction table (21 columns) with calculated fields |
| **Pivot Table** | 13 pivot tables that feed every KPI and chart |
| **Dashboard** | Final interactive view with KPI cards, charts and slicers |

**Dataset:** 2,707 orders · Jan–Dec 2026 · 4 regions · 17 countries · 4 sales channels · 3 customer types · 5 categories · 20 products

**Calculated columns** (built with Excel Table structured references):

```
Revenue        = Units Sold × Unit Price × (1 − Discount %)
COGS           = Units Sold × Unit Cost
Gross Profit   = Revenue − COGS
Gross Margin % = Gross Profit ÷ Revenue
Quarter        = "Q" & ROUNDUP(MONTH(Order Date)/3, 0)
```

## 🧰 Skills Demonstrated

- **Data modelling:** Excel Tables, structured references, derived date fields
- **Analysis:** PivotTables, KPI design, margin and discount analysis
- **Visualisation:** line, bar, pie and donut charts, with a consistent colour theme
- **Interactivity:** slicers for Product Category, Quarter and Country
- **Business thinking:** turning numbers into recommendations, not just charts

---

## 🚀 How to Use It

1. Download `Sales Dashboard by Category & Product Performance.xlsx` from this repo.
2. Open the **Dashboard** sheet.
3. Click the slicers (Category, Quarter, Country) and watch every chart update.
4. Go to the **Pivot Table** sheet to see how each number is calculated.

*Best viewed in desktop Excel (Microsoft 365 or Excel 2019+).*

---

## 🔭 What I'm Building Next

- Rebuilding this dashboard in **Power BI** with DAX measures
- Pulling the same data with **SQL** to practise the analysis outside Excel
- Adding a **forecast** for seasonal demand

---

## 👋 About Me

I'm **Shubhankar (Suvo) Mondal**, based in Kolkata, India. I work as a Junior Accountant, where my day-to-day is Tally Prime, GST reconciliation (GSTR-1/3B), TDS and stock reconciliation. I also hold a B.Tech in Mechanical Engineering (DGPA 8.57). That mix of accounting discipline and an engineering mindset is why I enjoy data work: I like numbers that reconcile and insights that someone can act on.

I'm moving into **data analytics** and looking for a Data Analyst or Business/Finance Analyst role.

**Certifications:** Microsoft Excel & Copilot Fundamentals · Microsoft Advanced Data Analysis & Visualization

**Tools:** Excel (PivotTables, XLOOKUP, SUMIFS) · Power BI *(learning)* · SQL *(learning)* · Tally Prime

📫 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/YOUR-HANDLE) · [Email](mailto:YOUR-EMAIL)

⭐ If this project was useful or interesting, a star on the repo is appreciated.
