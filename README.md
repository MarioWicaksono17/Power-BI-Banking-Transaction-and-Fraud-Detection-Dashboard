# Power-BI-Banking-Transaction-and-Fraud-Detection-Dashboard

This project presents an analytical dashboard built with Power BI to explore banking transaction patterns and detect potential fraudulent activities. It is designed to demonstrate data analytics skills relevant to the banking and financial services sector.

## Dashboard Pages

The dashboard consists of three main pages, each designed to deliver specific analytical insights:

1️⃣ Banking Transaction Overview (Page 1)

A high-level summary of all banking transactions:
- Total number of transactions
- Total transaction amount
- Total transaction by time
- Transaction status by number of transactions
- Fraud flag by number of transactions
- Transaction type by number of transactions
- Geographic distribution of transactions

2️⃣ Fraud Detection (Page 2)

A dedicated page for fraud monitoring and intelligence:
- Number of fraudulent transactions
- Fradulent transactions amount
- Transaction status by number of fradulent transactions
- Bandwith group by number of fradulent transactions
- Network slice by number of fradulent transactions
- Geographic distribution of fradulent transactions

3️⃣ Transaction Details (Page 3)

A detailed transaction table for exploratory analysis:
- Full transaction records
- Slicers and filters for ad-hoc investigation

## Tools and Technologies

- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)

## Methodology

### 1. Data Import
- Imported the raw banking transactions CSV file into Power BI Desktop.
- Reviewed the schema to understand available fields such as transaction amount, timestamp, customer info, and fraud indicators.

### 2. Data Cleaning & Transformation (Power Query)
- Removed invalid or failed transaction rows.
- Split the latitude/longitude field into two separate columns.
- Extracted the **time** component from the existing `timestamp` field and converted it into a proper Time data type.
- Converted the original `timestamp` column into Date format for time-series analysis.
- Ensured all columns had correct and consistent data types.

### 3. Data Modeling
- Loaded the transformed data into the Power BI model.
- Created additional calculated columns where needed.

### 4. DAX Measures
Developed several DAX measures to support analysis and visualization, including:
- Total Transactions  
- Total Fraud Cases  
- Fraud Rate  
- Average Transaction Amount  
- Transaction Trends (Daily/Monthly)

### 5. Visualization
- Built interactive dashboards using Power BI visuals.
- Designed pages for transaction overview, fraud detection, and detailed analysis.
