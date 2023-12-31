# STOCK TRENDS ANALYSIS
This Python script provides an interface to the Alpha Vantage API, allowing users to retrieve various financial data for stocks and cryptocurrencies. It leverages the Alpha Vantage API to access features such as monthly and weekly stock data, intraday stock data, income statements, and more.

# Prerequisites
Before running the script, ensure you have the following dependencies installed:

* requests
* beautifulsoup4
* pandas
* alpha_vantage

## You can install these dependencies using the following command:
    pip install requests beautifulsoup4 pandas alpha_vantage

# Usage
## 1. API Key

    Ensure you have an API key from Alpha Vantage and save it in a file named API_key.txt.

## 2. Running the Script
    Run the script using the following command:
    python alpha_vantage_api.py

The script will prompt you to enter a stock symbol. You can also uncomment and set a default symbol in the main() function.

## 3. Output

The script will provide you with the following information:

    Weekly stock data for the specified symbol.
    Monthly stock data for the specified symbol.
    Income statement for the specified symbol.
    Alpha Vantage API Functions
    get_monthly_stock_data(symbol): Retrieve monthly stock data for a given symbol.
    get_weekly_stock_data(symbol): Retrieve weekly stock data for a given symbol.
    get_intraday_stock_data(symbol): Retrieve intraday stock data for a given symbol.
    get_weekly_stock_data_df(symbol): Retrieve weekly stock data as a Pandas DataFrame.
    get_income_statement(symbol): Retrieve the income statement for a given symbol.