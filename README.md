# Project Name: Sales ETL Pipeline

## Objective
Build a PySpark ETL pipeline to process sales data, clean it, aggregate daily totals, and store results as Parquet files.

## Dataset
- CSV files stored in `data/`
- Sample dataset: sales_sample.csv

## Project Structure
- `data/` → Input datasets
- `scripts/` → PySpark ETL scripts
- `notebooks/` → Exploratory analysis
- `output/` → Processed results

## Steps to Run
1. Activate Python virtual environment:

   source ~/pyspark_env/bin/activate

2. Navigate to project folder and run script:

   python scripts/etl_pipeline.py

3. Check output in output/ folder.
