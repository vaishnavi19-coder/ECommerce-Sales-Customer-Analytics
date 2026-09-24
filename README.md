# E-Commerce Sales & Customer Analytics Dashboard

## Goal
Build an advanced, portfolio-ready Power BI dashboard from the supplied six-table e-commerce dataset.

## Included
- 6 cleaned-source CSV files
- Advanced DAX measure pack
- Professional dark Power BI theme
- Star-schema relationship map
- Page-by-page dashboard blueprint
- Advanced feature checklist

## Advanced Features
- Star schema
- Time intelligence (YTD, MTD, YoY)
- Dynamic metric selector
- Dynamic titles
- Top-N selector
- Ranking
- Drill-through
- Report page tooltips
- Bookmark filter drawer
- Reset filters
- Conditional formatting
- KPI cards
- Cross-filtering
- Executive website-style navigation

## Important limitation
This package does NOT contain a generated .PBIX file. Power BI Desktop's proprietary report binary is not something I can reliably generate here without Power BI Desktop itself. The package is designed so you can import the six CSVs, apply the included theme, paste the DAX measures, and build the report exactly from the blueprint.

## Recommended build order
1. Import CSVs
2. Power Query type checks
3. Create relationships
4. Mark DimDate as Date table
5. Add YearMonthSort
6. Add DAX measures
7. Apply theme
8. Build Page 1
9. Build Pages 2–5
10. Add drill-through page
11. Add bookmarks, tooltips and navigation
12. Validate totals and filters
13. Publish to Power BI Service

## Dataset
FactSales: 20,000 rows
DimCustomer: 5,000 rows
DimProduct: 500 rows
DimDate: 731 rows
DimPayment: 5 rows
DimShipping: 3 rows
