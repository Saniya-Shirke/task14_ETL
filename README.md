# task14_ETL

## Objective
Build a simple ETL pipeline using Python to clean, transform, and load retail sales data.

## Tools Used
- Python (Jupyter Notebook)
- pandas
- SQLite

## ETL Steps

### Extract
- Loaded raw CSV dataset from the `raw/` folder.

### Transform
- Removed duplicates.
- Checked and handled missing values.
- Standardized column names.
- Converted data types (date → datetime, amounts → float).
- Created new columns:
  - calculated_total
  - high_value_flag

### Load
- Saved cleaned data to `processed/processed_data.csv`.
- Split data into:
  - customers table
  - transactions table
- Loaded tables into `database.sqlite`.
- Validated row counts after processing.

## Files Included
- task14_etl.ipynb
- processed/processed_data.csv
- output/customers.csv
- output/transactions.csv
- database.sqlite

## Outcome
Understood practical implementation of an ETL pipeline in analytics workflows.
