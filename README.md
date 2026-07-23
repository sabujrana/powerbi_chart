## 📊 Power BI Dashboard

An interactive Power BI report analyzing jewelry e-commerce sales data (2019–2021).

### Dataset
Transaction-level records including `Datetime`, `OrderID`, `ProductID`, `CategoryID`, `BrandID`, `USDPrice`, `UserID`, `Gender`, `Color`, `Metal`, and `Gem` type.

## 📈 Chart Details

### chart1.png — Overview (Page 1)
- **Bar Chart**: Sum of USDPrice by Jewelery_Type — earrings and rings are the top-selling categories, far ahead of bracelets, pendants, necklaces, brooches, clocks, and souvenirs
- **Pie Chart**: Sum of USDPrice by Color — red leads with ~70.78% ($16.3M), followed by white ~22% ($5.07M) and yellow ~7.21% ($1.66M)
- **Line Chart**: Sum of USDPrice by Year and Quarter — shows a consistent upward revenue trend from 2019 through 2021

### chart2.png — Daily Trend by Color (Page 2)
- **Line Chart**: Sum of USDPrice by Year, Quarter, Month, and Day — segmented by Color (red, white, yellow)
- Highlights daily-level volatility and sales spikes, with red consistently outperforming other colors
- Supports drill-down to exact date-level detail (e.g., tooltip shows "2019 Qtr 3, September 8" with per-color breakdown)

### chart3.png — Category Breakdown (Page 3)
- **Donut Chart**: Sum of USDPrice by Jewelery_Type — same category distribution as chart1, shown with percentage labels
- **Icicle Chart**: Sum of USDPrice by Year and Color — hierarchical view of color-wise sales within each year (2019, 2020, 2021)
- **Forecast Line Chart**: Sum of USDPrice over time with a projected trend and widening confidence band further into the future

### chart4.png — Forecast Detail (Page 4)
- **Line Chart**: Sum of USDPrice by Year and Quarter, with forecasted confidence interval shown as a shaded band
- Tooltip example ("2021 Qtr 3"): Actual value ~$4.55M vs. Expected value ~$4.64M (range: $3.94M–$5.34M)
- Useful for evaluating forecast accuracy and understanding the range of expected outcomes
### Key Features
- Drill-down/drill-up navigation across Year → Quarter → Month → Day
- Forecasting with confidence intervals to project future sales
- Cross-filtering between visuals for interactive exploration
- Breakdown by product category, color, and metal type

### Tools Used
- **Power BI Desktop** for data modeling, DAX measures, and visualization

# Author: Sabuz Rana