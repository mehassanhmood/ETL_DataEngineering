# ETL_DataEngineering
**ETL process :  Disparate sources to target format.**
>*I performed the ETL (Extract, Transform, Load) process on bank and market capitalization data. Here's a summary of what I accomplished:*

## Objectives
In this assignment, I achieved the following objectives:

  1. Ran the ETL process.
  2. Extracted bank and market cap data from JSON files.
  3. Transformed the market cap currency using exchange rate data.
  4. Loaded the transformed data into a separate CSV.
## Summary of My Work
### Extract
I used the provided extract_from_json function to read JSON files and loaded the data into a Pandas DataFrame. This initial step allowed me to access and prepare the data for further processing.

### Transform
I successfully implemented the transform function. This function adjusted the market capitalization column to British pounds (GBP), rounded it to three decimal places, and renamed the column to "Market Cap (GBP$ Billion)."

### Load
In the final step, I made the load function. This function accepted a DataFrame and saved it to a CSV file named bank_market_cap_gbp.csv. I ensured that the index was not included in the saved CSV.

### ETL Process Execution
I followed the provided instructions to execute the ETL process seamlessly. 
I logged the different phases of the process:
  1. ETL Job Started
  2. Extract phase Started
  3. Extract phase Ended
  4. Transform phase Started
  5. Transform phase Ended
  6. Load phase Started
  7. Load phase Ended.

### Key Takeaways
Completing this assignment demonstrated my ability to perform ETL tasks, work with different data formats, and effectively utilize Python libraries for data manipulation. The ETL process is a fundamental aspect of data engineering, and my successful completion of this assignment showcases my skills in data preparation and transformation.

