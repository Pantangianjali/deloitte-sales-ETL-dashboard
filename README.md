# Deloitte Sales ETL + Power BI Dashboard

End-to-end sales analytics project replicating Alteryx workflows.

## Tech Stack
- **ETL**: Python, Pandas
- **BI**: Power BI Desktop
- **Data**: Superstore Sales Dataset

## ETL Pipeline
`etl/etl_script.py` cleans raw data:
- Handles null dates and customer names
- Converts Sales/Profit columns to float
- Outputs `superstore_clean.csv` for analysis

## Power BI Dashboard
Interactive dashboard tracking **$2.30M Sales** and **$286.40K Profit** across:
1. Sales by Region
2. Profit by Category  
3. Sales by Segment
4. Top Sub-Categories
5. Region Slicer for drill-down

## Results
Built complete analytics solution from broken PBIX file to working dashboard in one session.
