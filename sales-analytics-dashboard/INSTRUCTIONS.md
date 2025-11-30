Quick Excel Dashboard steps (for beginners)
1. Open `data/sales_data.csv` in Excel.
2. Convert to Table: Home -> Format as Table (helps for pivot refresh).
3. Insert -> PivotTable -> Select Table/Range -> New Worksheet.
4. Build recommended PivotViews:
   - Monthly Sales: Rows = Date (Group by Month), Values = Sum of Revenue.
   - Regional Performance: Rows = Region, Values = Sum of Revenue, Sort Descending.
   - Top Products: Rows = Product, Values = Sum of Revenue, Filter Top 10.
5. Insert charts for each pivot (PivotChart). Add Slicers: PivotTable Analyze -> Insert Slicer -> Region, Product.
6. Create a KPI area: use simple formulas referencing pivot values (e.g., =GETPIVOTDATA(...)).
7. Save workbook and export as PDF if needed.

Files to upload: `Sales_Dashboard_YourName.xlsx` (or export_example.csv if you prefer).
