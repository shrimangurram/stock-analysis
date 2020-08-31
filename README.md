# An Analysis of Green Energy Stocks Performance
Perform data analysis on Green Energy Stocks Performance for 2017 and 2018
---

## Challenge

Link to the analysis spreadsheet:
[Stock Analysis Spreadsheet](https://github.com/shrimangurram/stock-analysis/blob/master/green_stocks.xlsm)

### Analysis Report
Analyzing the performance of the selected Green Energy Stocks:
* 2018 has been a bad year for Green Energy Stocks. Except for ENPH and RUN, rest of the stocks have had a negative return. DAQO stock has performed poorly compared to the rest of the stocks
* 2017 was a good year for almost all of the Green Energy Stocks except for TERP. DAQO had one of the best returns amongst all the stocks
---
Refactored Code Logic:
* Initialize array variables for ticker, total volume, starting price and ending price
* Set ticker index to 0
* Initialize total volume array values to 0
* Get total row count
* Loop through all rows and get total volume, starting price and ending price for each ticker and store in the corresponding array variable 
* Increment tickerIndex by 1 once the ending price is determined to get the info for the next ticker ---
* Loop through the arrays for ticker, total volume, starting price and ending price and populate the 'All Stocks Analysis Refactored' worksheet
