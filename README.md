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
<img width="1317" height="731" alt="KPI analysis" src="https://github.com/user-attachments/assets/dc7eba92-a851-40c4-9791-ad9b9e0e2805" />
<img width="1326" height="735" alt="country sales analysis" src="https://github.com/user-attachments/assets/e4f03d11-b0fe-4168-90a0-8bc0c5c5d133" />
## Key insights (Apr 2021 – Apr 2024)

- **£10M total revenue** and **£1.19M gross profit**, a **12.1% gross margin**.
- **EU is the largest market** at £2.6M, followed by APAC (£2.0M). Africa contributes the least.
- **Technology is the top category** (37.4% of revenue), but the split is balanced: Furniture 31.6%, Office Supplies 31.0%.
- Revenue peaked at about **£0.47M a month in early 2024**, but it swings sharply from month to month.
