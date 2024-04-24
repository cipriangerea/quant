This is a script that is trying to show what happens with the various tickers used by a symphony. It consists of a notebook that is written to be used inside Google Colab.

# How to use this: 
- Go to Composer and in edit mode run a backtest of the symph. (Also works with QuantMage).
- Save the historical allocation csv
- Open the StrategyAllocationVis.ipynb notebook in Colab
- Run all cells. From the menu select Runtime/Run all
- The second cell has a file picker, open the csv

# How to use the results
1. Look at portfolio allocation over time. Chart is zoomable. Double click a symbol in the legend and it's going to show only that symbol.
2. Look at the last table, it shows some per-ticker stats. Most interesting is how much profit that ticker produced assuming $100k invested in the whole symph.

# How to troubleshoot?
We can have errors if yfinance doesn't have tickers. You need to find the ticker in yfinance and map it like we do with BRK/B
