# MARKETPULSE | Supermarket Sales & Business Intelligence Dashboard

## Project Overview
MARKETPULSE is an Excel-based supermarket sales analytics project. It explores sales performance across product lines, cities and branches, customer segments, payment methods, months, and time of day. The goal is to turn transaction data into understandable visual insights and practical questions for business decision-making.

## Objectives
- Summarize sales performance using key performance indicators (KPIs).
- Compare sales across product lines, cities, branches, and customer types.
- Explore payment-method preferences and transaction patterns.
- Review monthly and time-of-day sales trends.
- Translate observations into business recommendations that can be tested.

## Tools
- Microsoft Excel
- Excel formulas, charts, dashboard formatting, and dropdown-based filters
- PowerPoint for the project presentation

## Project Files
- MARKETPULSE_README-Explains Files.
- `Supermarket_Sales_Analytics_Project.xlsx` — project workbook containing source data and analysis material.
- `Supermarket_Sales_Dashboard.png` — dashboard preview image.
- `Supermarket_Sales_Project_Presentation.pptx` — presentation for explaining the project and its findings.

## Analysis Areas
1. Product-line sales performance
2. City and branch comparison
3. Payment-method sales and transaction counts
4. Monthly sales trends
5. Customer-type and gender segmentation
6. Time-of-day sales patterns
7. Areas for further investigation and potential business improvements

## Key Observations
The following observations were reported during the project analysis and should be checked against the workbook before being presented as final findings:
- Food and Beverages was reported as the highest-selling product line, followed by Sports and Travel.
- Naypyitaw was reported as the highest-sales city among the values shared; Mandalay was reported as the lowest.
- E-wallet payments were reported to have more transactions and higher sales than credit-card payments.
- January was reported as the highest-sales month and February as the lowest.
- Evening sales were reported as higher than morning sales.
- Home and Lifestyle was reported as the weakest-selling category in Branch C.
- Electronics Accessories was reported to have a notable sales drop in February.
- Lower evening sales in Yangon and lower March sales for females in Health and Beauty were identified as areas to investigate.

These are descriptive observations, not proof of the causes behind the patterns. Validate the values and definitions in Excel before publishing them.

## Potential Business Recommendations
- Investigate category performance in Mandalay, especially Food and Beverages and Fashion Accessories.
- Review February's sales decline, particularly Electronics Accessories, checking stock availability, pricing, promotions, and transaction volume.
- Test targeted promotions for Normal customers and measure the impact.
- Explore morning offers and review staffing, product availability, and service efficiency.
- Review Home and Lifestyle assortment and stock availability in Branch C.
- Investigate March's Health and Beauty performance by customer segment before changing inventory or promotions.
- Test evening offers in Yangon and compare results with a baseline period.

Recommendations should be treated as hypotheses to test. Do not claim that a promotion or operational change will improve sales until its results are measured.

## How to Use the Dashboard
1. Open `Supermarket_Sales_Pro_Dynamic_Dashboard.xlsx` in desktop Microsoft Excel.
2. Enable editing if prompted.
3. Use the dropdown filters at the top of the Dashboard sheet to filter by Branch, City, Customer Type, Gender, Product Line, Payment, Month, and Time of Day.
4. Review the KPI cards and charts after changing a filter.
5. If formulas do not refresh immediately, use **Formulas → Calculate Now** or press **Ctrl + Alt + F9** to force recalculation.
6. Chart helper calculations are available on the `ChartData` sheet. The `Color Guide` sheet explains how to customize chart colors.

Note: The dashboard's dropdown filters use worksheet formulas. They are not the same as native Excel slicers, and they may not control unrelated PivotCharts unless those PivotCharts are separately connected to compatible PivotTables and slicers.

## Important Data Notes
- Confirm all numerical findings against the source workbook before using them in a report or interview.
- The dataset covers January–March 2019; avoid describing this as current market data.
- In this dataset, the `gross income` field should not be described as net profit without additional cost information.
- Use the currency/units shown in the source dataset and dashboard; do not infer a currency if it is not explicitly specified.
- Some findings shared during project development may be preliminary and require validation.

## Resume Description
**MARKETPULSE — Supermarket Sales & Business Intelligence Dashboard | Microsoft Excel**  
Built an interactive Excel dashboard to analyze supermarket sales by product line, city/branch, customer segment, payment method, month, and time of day. Developed KPI summaries and visualizations to identify performance patterns and propose data-driven areas for further investigation.

## Future Improvements
- Add verified KPI definitions and a data dictionary.
- Create a dedicated insights page with validated metrics.
- Connect slicers consistently if the dashboard is migrated to PivotTables/PivotCharts.
- Add a documented validation process for findings and recommendations.
- Track the impact of promotional recommendations using a future-period comparison.

---
Created for the MARKETPULSE portfolio project.
