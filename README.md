# Retail Orders ETL & SQL Analysis 🛒

## Project Description
This project demonstrates an end-to-end Data Engineering pipeline. I extracted raw retail data using the **Kaggle API**, cleaned and transformed the data using **Python (Pandas)**, and loaded it into a **Microsoft SQL Server** database for further analysis.

## Pipeline Architecture
1. **Extraction**: Programmatic download from Kaggle.
2. **Transformation**: 
   - Cleaned messy column names.
   - Handled data types (Date conversion).
   - Engineered new features (Sale Price, Profit, Discount).
3. **Loading**: Connected to SQL Server using `SQLAlchemy` and pushed data using the `to_sql` method.

## How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Add your `kaggle.json` to your local path.
4. Run the notebook in `notebooks/Retail_Orders_ETL.ipynb`.