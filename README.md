## 🧹 Data Preparation

- Cleaned and transformed the dataset using **Power Query Editor** in Power BI
- Removed duplicates, handled missing values, and standardized column formats
- Created custom columns and metrics using **DAX (Data Analysis Expressions)**

### 🧮 DAX Formulas Used

Some key DAX functions and measures applied include:

- `CALCULATE()` – for dynamic aggregations based on filters
- `FILTER()` – to apply conditional logic across tables
- `COUNTROWS()` and `DISTINCTCOUNT()` – for unique counts (e.g., employees by department)
- `SWITCH()` – to categorize employment types
- `IF()` – for conditional logic (e.g., resignation status)
- `RELATED()` – to fetch related data from other tables (if applicable)
- Time Intelligence functions like `TOTALYTD()` or `DATEADD()` (if used for trend lines)

## 🚀 Getting Started

To explore or rebuild the dashboard:

1. Open Power BI Desktop.
2. Load the dataset from `HR Data.xlsx`.
3. Use **Power Query Editor** to inspect the data cleaning steps.
4. Explore the **DAX measures** and calculated columns used for visualizations.
5. Refer to `HR Report.pdf` to see the final design and insights.
