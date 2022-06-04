# S-P500-Stocks-Visualization
utilize pandas dataframe and plotly, widgets to analyze and visualize data

### Transaction Table
##### This table contains Date, Ticker, Amount, and BuySell column, it is a customized portfolio

### Scaffold Table
##### This table merge the transaction table, reference table, and the stock data of each ticker in my portfolio
##### This is a time-series data table, created by using the create_join_table(date) function with the passed-in date

### PnL
##### ‘PnL’ (Profit and Loss) is your total portfolio profit/loss at any given point in time. For a given stock, the daily marked-to-market PnL is simply the return*position. Add acolumn containing the daily PnL for each ticker.
