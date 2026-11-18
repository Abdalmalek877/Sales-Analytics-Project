# 📊 Sales Analytics Project

An interactive **Power BI** business intelligence dashboard analyzing US retail sales, profitability, customer demographics, and product performance from **2014 to 2017**[cite: 1, 2].

---

## 📌 Project Overview

This project transforms raw retail transaction data into a multi-page visual analytics report designed to uncover revenue drivers, margin efficiency, geographic distribution, and year-over-year growth trends[cite: 1, 2].

### 🎯 Key Performance Indicators (KPIs)
* **Total Sales:** `$2,297,200.86`[cite: 1]
* **Total Profit:** `$286,397.02`[cite: 1]
* **Profit Margin:** `12%` (`0.12`)[cite: 1]
* **Total Orders:** `5,009`[cite: 1]
* **Total Customers:** `793`[cite: 1]
* **Total Records / Transactions:** `9,994`[cite: 1]

---

## 📈 Dashboard Breakdown

### Page 1: Executive Summary & Geographic Overview
* **KPI Cards:** High-level tracking of Total Sales, Total Profit, Total Orders, Total Customers, and Profit Margin[cite: 1].
* **Count of Region by Quantity:** Column chart showing order volume distribution across item quantities (peaking at quantities of 2 and 3)[cite: 1].
* **Count of City & Customer ID by Category:** Donut chart breaking down the `9.994K` records across product categories (`60.3%`, `21.22%`, `18.48%`)[cite: 1].
* **Geographic Sales Map:** Interactive Bing Map visualizing customer and city distribution across the United States[cite: 1].
* **Sales & Country Count by Profit:** Line chart tracking revenue fluctuations across profit margins (`-5K` to `10K`)[cite: 1].
* **Transaction Gauge:** Progress gauge tracking total dataset records (`9,994` out of `19.99K` target scale)[cite: 1].

### Page 2: Category, Product & Yearly Trends
* **Yearly Performance Breakdown (2014–2017):** Pie chart illustrating steady year-over-year growth[cite: 2]:
  * **2014:** `1.99K` (`19.94%`)[cite: 2]
  * **2015:** `2.10K` (`21.03%`)[cite: 2]
  * **2016:** `2.59K` (`25.89%`)[cite: 2]
  * **2017:** `3.31K` (`33.14%`)[cite: 2]
* **Category Volume Comparison:** Horizontal bar chart comparing order counts across **Office Supplies** (~`6.03K`), **Furniture** (~`2.12K`), and **Technology** (~`1.85K`)[cite: 1, 2].
* **Order Date Count & Total Profit by Sales:** Dual-axis line chart highlighting profit volatility at lower sales tiers versus higher-value transactions[cite: 2].
* **Top Performing Products:** Detailed bar chart ranking individual `Product ID`s by order frequency (led by `OFF-PA-10001970` and `TEC-AC-10003832`)[cite: 2].

---

## 🛠️ Tools & Technologies

* **BI & Visualization:** Microsoft Power BI Desktop (Bing Maps integration, DAX measures, KPI cards, interactive charts)[cite: 1]
* **Data Source:** US Superstore / Retail Sales Dataset (`9,994` rows, `2014–2017`)[cite: 1, 2]
* **Export Format:** PDF / `.pbix`[cite: 1]

---

## 💡 Key Insights

1. **Consistent YoY Growth:** Transaction volume grew steadily every year from `19.94%` in 2014 to `33.14%` in 2017[cite: 2].
2. **Category Dominance:** **Office Supplies** accounts for over `60%` of total transaction volume, making it the primary driver of customer order frequency[cite: 1, 2].
3. **Order Size Sweet Spot:** Customers most frequently purchase items in quantities of **2 to 3 units** per order line[cite: 1].
4. **Healthy Baseline Margin:** Across `$2.30M` in gross revenue, the business maintains an overall **12% profit margin** (`$286.4K` net profit)[cite: 1].

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
