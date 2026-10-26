# Sales Performance Dashboard (Power BI)

An interactive three-page Power BI report that tracks revenue, gross profit and margin across markets,
countries, product categories and sales directors, and measures performance against revenue targets.
Built as part of my BSc (Hons) Business Technology at Manchester Metropolitan University.

<!-- Add a screenshot of each page here, e.g.:
![Overall Sales Analysis](images/overall-sales.png)
![Country Sales Analysis](images/country-sales.png)
![KPI Analysis](images/kpi-analysis.png)
-->

## Business questions it answers

- How much revenue and gross profit are we making, and at what margin?
- Which markets, countries and cities drive the most revenue?
- Which product categories (Technology, Office Supplies, Furniture) sell best, and where?
- How is revenue trending over time?
- Which markets and sales directors are hitting their revenue targets, and which are falling short?

## Report pages

| Page | What it shows |
|---|---|
| **Overall Sales Analysis** | KPI cards (Total Revenue, Total Gross Profit, Gross Profit Margin), revenue by market, revenue by category, and a revenue trend line with a date-range slicer |
| **Country Sales Analysis** | A map of revenue by city and country, a revenue and margin matrix over time, and the category split for the selected country |
| **KPI Analysis** | Bullet charts comparing actual revenue with target by market and by sales director, a category mix by market, and unit price analysis |

## Data model

A relational model with **Orders** at the centre, linked to **Customers**, **Products**, **Shipping**,
**Returns**, **Sales_Directors** and a **KPIS** table of revenue targets. DAX measures calculate
Total Revenue, Total Gross Profit and Gross Profit Margin, and they respond to every slicer and filter.

## Skills demonstrated

- Data modelling and table relationships
- DAX measures for revenue, profit and margin
- KPI and target tracking with bullet charts
- Geographic analysis with map visuals
- Time-series trend analysis and interactive slicers
- Page navigation and report design for non-technical users

## How to open it

1. Download `PowerBI MMU projects.pbix`.
2. Open it in [Power BI Desktop](https://www.microsoft.com/power-bi/desktop) (free, Windows).

## Author

**Chibuzo Prosper Onyiwe** · Business Technology, Manchester Metropolitan University ·
[LinkedIn](https://www.linkedin.com/in/prosper-onyiwe)

<img width="1917" height="817" alt="overall-sales" src="https://github.com/user-attachments/assets/4a80c2ef-ef37-4bee-9123-cc3c89080a7a" />
<img width="1162" height="642" alt="country sales analysis" src="https://github.com/user-attachments/assets/9b97302d-376c-4ee4-9f9d-6e7cecc3c570" />
<img width="1165" height="647" alt="KPI Analysis" src="https://github.com/user-attachments/assets/d6a1a5d2-99cd-4b5d-b27f-ac4b50b9e5e6" />

## Key insights

- **£15M total revenue** and **£1.75M gross profit**, a **12.0% gross margin** overall.
- **EU is the strongest market**: the highest revenue and well above its KPI target. LATAM also beats its target.
  **APAC is furthest below target**, followed by Africa, EMEA and Canada.
- **4 of the 7 named sales directors beat their revenue target**, led by Anna Andreadi, Chuck Magee and Jack Lebron.
- **Technology earns the most revenue** (around 37%) and has the highest average unit price (£136.88).
  **Office Supplies makes up the majority of orders** in every market but has the lowest unit price (£36.44),
  so it drives volume rather than value.
- **Country drill-down:** for example, Brazil generated £1.53M of revenue at a 13.5% margin, with October the
  most profitable month (20.2% margin).
