# Task 3 — Deep-Dive Analysis & Interactive Dashboarding

## Project
**Sales Performance Deep-Dive Analysis and Interactive Dashboard**  
ApexPlanet Software Pvt. Ltd. — Data Analytics Internship

## 1. Objective
Define core business KPIs, investigate sales performance in depth, and build an interactive dashboard for exploring sales by category, product, city, and month.

## 2. Dataset
The Task 2 README describes 1,000 sales transaction rows and 12 original columns, with `Month` and `Sales_Check` added for analysis. Export the cleaned data sheet as CSV and load it into the dashboard. Verify the column names and date/sales fields before interpreting results.

## 3. Core KPIs
| KPI | Formula | Business rationale |
|---|---|---|
| Total Sales | Sum of `Total Sales` | Measures revenue in the selected records. |
| Unique Orders | Count of distinct `Order ID` | Measures order volume without double-counting repeated IDs. Confirm the dataset's order-grain definition. |
| Average Order Value | Total Sales ÷ Unique Orders | Estimates revenue per unique order. |
| Units Sold | Sum of `Quantity` | Measures units sold. |
| Sales by Category | Sum of `Total Sales`, grouped by `Category` | Compares category contribution to revenue. |

## 4. Deep-dive analysis: sales performance and customer segmentation
The dashboard compares product, category, city, and monthly sales. It also groups customers using total sales in the filtered data:
- **High:** at or above the 75th percentile.
- **Medium:** between the 25th and 75th percentiles.
- **Low:** at or below the 25th percentile.

This is a transparent, rule-based sales segmentation, not a predictive model or full RFM analysis.

## 5. Interactive dashboard
Open `Task3_Interactive_Dashboard.html` in Chrome or Edge. Export the cleaned data sheet as CSV and select the file in the dashboard. It contains KPI cards, Category/City/Month filters, sales charts, customer segmentation, and a data preview. The selected file is processed locally in the browser.

## 6. Findings and recommendations
**Fill this section after loading the real cleaned dataset.** Record the actual top category, top product, top city, strongest/weakest month, and segment counts. Do not use sample or invented values as findings.

Potential recommendations, once supported by the results:
1. Protect stock availability for consistently high-performing products.
2. Investigate low-performing products or cities before changing prices or inventory.
3. Check monthly trends for seasonality and completeness of the date range.
4. Consider retention or cross-selling strategies for high-value customers.
5. Validate repeated order IDs and unusual values before final business conclusions.

## 7. Limitations
- Findings depend on the cleaned CSV actually loaded; verify KPI totals against Excel.
- Repeated Order IDs need to be interpreted using the dataset's grain.
- Segments use sales only; they do not account for recency, purchase frequency, margins, or profitability.
- The HTML file is locally interactive. A public live dashboard URL requires publishing it with GitHub Pages or a BI hosting service.

## 8. Deliverables
- Interactive dashboard HTML
- This deep-dive report
- README and LinkedIn walkthrough script

## Conclusion
The dashboard provides an interactive way to explore the cleaned sales data. Final business findings should be recorded only after loading and validating the actual dataset.
