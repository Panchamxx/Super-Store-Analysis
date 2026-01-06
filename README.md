# Superstore Sales Analysis

## Project Overview
This project analyzes the **Superstore sales dataset** to uncover sales trends, top-performing products, and customer insights. It demonstrates an end-to-end data analysis workflow including **data cleaning, validation, SQL queries, and dashboard visualization in Power BI**.

---

## Data
- **Sample - Superstore.csv**: Original Kaggle Superstore dataset.
  - Imported into SQL for cleaning and analysis.
  - All data cleaning (duplicates, missing values, column standardization) is performed in SQL.

---

## Workflow

1. **Clean Final Table**
   - Created a clean table (`Superstore_Final`) in SQL.
   - Removed duplicates, standardized column names, and handled missing values.

2. **Insert Clean Data**
   - Loaded raw CSV data into the clean SQL table.

3. **Data Quality Checks**
   - Validated row counts, checked for nulls and duplicates.
   - Ensured data consistency and integrity before analysis.

4. **Analysis Queries**
   - Generated insights such as:
     - Sales by region
     - Top-selling products
     - Monthly trends

---

## Tools Used
- **SQL**: Data cleaning, transformation, and analysis queries.
- **Power BI**: Dashboard creation and visualization.
- **Excel**: Optional for intermediate checks or quick exploration.

---

## Dashboard
- **PBIX file**: `Super Store Dashboard.pbix`
- **Screenshots**: See Dashboard Screenshot folder
- Dashboard features:
  - Interactive slicers for region
  - Key sales, profit, and quantity visualizations
  - Monthly and category trends

---

## Key Insights
1. Total sales: $2.3M, Total profit: $286k → ~12.5% profit margin.
2. Technology drives highest sales and profit; Furniture has high sales but very low profit.
3. West region leads in sales and profit; South is small but profitable; Central shows margin issues.
4. Peak sales in Q4; some months show losses despite sales.
5. Top 10 products mostly Technology; a few top-sellers have negative profits, highlighting margin challenges.

---

## Repository Structure


---

## How to Use
1. Open `Sample - Superstore.csv` in your SQL environment to follow the workflow.
2. Run SQL scripts in order:  
   - `1. Create Clean Final Table` → `2. Insert Clean Data` → `3. Data Quality Checks` → `4. Analysis Queries`  
3. Open `Super Store Dashboard.pbix` in Power BI Desktop to view interactive visualizations.

---

## Notes
- All analysis and dashboards are based on the Kaggle Superstore dataset.
- No sensitive or personal data is included.

