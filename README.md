# � FestMan Stores Financial Analysis Dashboard  
![Dashboard Preview](images/dashboard_preview.png)

## 📈 Key Insights
- **$92.3M sales** (+249.46% YoY growth)
- **86K orders** with 14.1% discount impact
- **Profit margins**: Germany (15.7%), France (15.5%)
- Top products: Paseo (33.01% of sales), VTT (20.5K units)

## 🔍 Features
✔ **Interactive KPIs**:  
  - YoY comparisons (sales, orders, discounts)  
  - Segment-level profit margins (Enterprise: 3.13%, Channel Partners: 73.13%)  

✔ **Geographic Analysis**:  
  - Sales and margins by country (US, Canada, Germany)  
  - Discount band breakdown (High: 37.76%, Medium: 32.62%)  

✔ **Time Intelligence**:  
  - Monthly sales trends (2014-2015)  

## 🚀 Setup
1. **Download** [`FestMan_Financial_Analysis.pbix`](FestMan_Financial_Analysis.pbix)
2. **Connect data**:  
   - Replace sample data in `/data/FestMan_Sales_Data.xlsx` with your dataset
3. **Customize**:  
   - Adjust DAX measures (e.g., `Profit Margin = DIVIDE([Profit], [Sales])`)

## 📂 Files
| File | Description |
|------|-------------|
| `.pbix` | Power BI report with all visuals |
| `/data/*.xlsx` | Synthetic sales data (orders, products, countries) |
| `/images/*.png` | Annotated dashboard screenshots |

## ⚠️ Notes
- Sample data covers 2014-2015. Update for recent years.
- Government segment has incomplete product coverage.
