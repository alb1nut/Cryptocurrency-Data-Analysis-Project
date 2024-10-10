# Cryptocurrency Data Analysis Project

## Project Overview

This project analyzes cryptocurrency data by extracting information from the CoinCap API. It aims to explore relationships between various attributes, including rank, supply, market capitalization, and price. The analysis focuses on restructuring and cleaning the data to ensure accuracy and usability.

## Objectives

- Extract cryptocurrency data from the CoinCap API.
- Transform and clean the data for analysis.
- Handle missing values and convert categorical data to numerical formats.
- Load the cleaned data into a PostgreSQL database for further exploration.

## Data Processing Steps

1. **Import Libraries**
   - Utilize libraries such as `pandas` for data transformation and `requests` to establish a connection with the API.

2. **Extract Data**
   - Fetch data from the CoinCap API and convert it to JSON format.

3. **Transform Data**
   - Normalize the JSON data into a DataFrame.
   - Convert specific columns to appropriate data types.

4. **Handle Missing Data**
   - Fill missing values with appropriate defaults.

5. **Round Numbers**
   - Round numerical values to two decimal places for consistency.

6. **Load Data into PostgreSQL**
   - Establish a connection to a PostgreSQL database.
   - Load the cleaned DataFrame into a specified table.

## Usage

- Ensure that the necessary libraries are installed and the PostgreSQL database is set up.
- Replace the database credentials with your own before running the script.
- Execute the script to fetch, process, and store cryptocurrency data.

## Conclusion

This project provides valuable insights into cryptocurrency data by analyzing various attributes and storing the processed data for further exploration.


