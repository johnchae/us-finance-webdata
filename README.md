# us-finance-webdata
This project uses Python, pandas, and pandas-datareader to import various types of financial data to try and determine the financial health and volatility of US assets between 1999 and 2019. Financial data will be imported with the provided csv files, FRED API, and the World Bank API.

Once data is imported, it finds the log returns of each data set using numpy and uses that to determine the volatility of the data over a 20 year period.
