# Lending Club Data Processing Project

## Project Overview
This project processes customer loan data from Lending Club using Apache Spark. It includes data transformations and SQL queries to clean and prepare the dataset for further analysis. The final processed data is saved into CSV files for easy access and use.

The project leverages Spark SQL to query, filter, and transform data based on various criteria, including customer information, loan repayments, and delinquency details.

## Project Structure
- `data/`: Folder containing the raw data files used in the project.
- `scripts/`: Folder containing the Spark scripts that perform the transformations.
- `output/`: Folder where the final CSV files are stored.
- `README.md`: This documentation file.

## Steps Involved
1. **Data Loading**: Raw data is loaded into Spark from various sources.
2. **Data Transformation**: SQL queries are executed to rename, filter, and join relevant columns to prepare the dataset.
3. **Data Saving**: The processed data is written back into CSV files with headers.
4. **Final Output**: The output consists of multiple CSV files, including:
   - `customers_data_csv`: Processed customer data with detailed information.
   - `loans_data_csv`: Processed loan-related data.
   - `loans_repayments_csv`: Processed loan repayment data.
   - `loans_defaulters_csv`: Data related to delinquencies and loan defaults.

## Technologies Used
- Apache Spark
- Spark SQL
- Python (PySpark)
- CSV
