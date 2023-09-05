# IBM Data Engineering Project: Exchange Rate ETL

## Objectives
The primary objective of this project is to demonstrate proficiency in data engineering, with an emphasis on the ETL (Extract, Transform, Load) process. The project involves extracting bank and market cap data, transforming the market cap currency from USD to GBP, and finally, loading the transformed data into a CSV.

## Summary
This project showcases the ETL process using Python and the pandas library. Starting with raw data in JSON format, various functions are employed to extract, transform, and load the data into a CSV file. The transformation includes currency conversion using exchange rate data.

## Dataset
The primary dataset is a JSON file named `bank_market_cap.json`. It contains bank and market cap data, which is then transformed using exchange rate data from a CSV file.

## Methodology

### 1. Extract
- Data is extracted from the JSON files into pandas dataframes.
- Custom functions are defined to handle the extraction process, ensuring modularity and repeatability.

### 2. Transform
- The `Market Cap (US$ Billion)` column's currency is converted from USD to GBP.
- Values are rounded to three decimal places for precision.
- Column names are updated to reflect the currency transformation.

### 3. Load
- The transformed data is loaded into a CSV file, `bank_market_cap_gbp.csv`, ensuring that the results are easily accessible and shareable.

## Libraries & Tools
- **pandas**: Used extensively for data extraction, transformation, and loading.
- **datetime**: Assists with date and time operations.
- **glob**: Aids in file operations, especially locating the required JSON file.

## Running the ETL Process
The project encapsulates the entire ETL process, from data extraction to transformation and loading. By running the Jupyter Notebook, the user can seamlessly extract data from the source, transform it based on business logic, and load it into a target CSV file.

