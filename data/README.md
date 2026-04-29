# Data Directory

## Structure
- `raw/` - Original, unmodified data files (PDFs from CBK)
- `processed/` - Cleaned CSV files ready for analysis

## Files Description

### Raw Data
- `CBK_Statistical_Bulletin_June_2024.pdf` - Original source document from CBK

### Processed Data
- `cbk_revenue_expenditure_2020_2024.csv` - Main dataset (revenue, expenditure, budget balance)
- `cbk_revenue_breakdown_2020_2024.csv` - Detailed revenue sources
- `cbk_expenditure_breakdown_2020_2024.csv` - Detailed expenditure categories

## Data Dictionary

### cbk_revenue_expenditure_2020_2024.csv
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Year | Integer | Fiscal year (2020-2024) |
| Period | String | Month (June) |
| Tax_Revenue_KSh_Millions | Float | Tax revenue in millions KSh |
| Non_Tax_Revenue_KSh_Millions | Float | Non-tax revenue in millions KSh |
| Total_Revenue_KSh_Millions | Float | Total government revenue |
| Grants_KSh_Millions | Float | Foreign grants received |
| Revenue_and_Grants_KSh_Millions | Float | Total revenue including grants |
| Recurrent_Expenditure_KSh_Millions | Float | Operational/recurrent spending |
| Development_Expenditure_KSh_Millions | Float | Capital/development projects |
| Total_Expenditure_KSh_Millions | Float | Total government expenditure |
| Budget_Balance_KSh_Millions | Float | Surplus/deficit (negative = deficit) |
| Deficit_as_Percentage_of_Revenue | Float | Deficit as % of total revenue |

## Source
Central Bank of Kenya Statistical Bulletin, June 2024
https://www.centralbank.go.ke/releases/statistical-bulletin/