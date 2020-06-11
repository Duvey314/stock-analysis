# Stock Analysis
This is an analysis of a sample stock portfolio for a client. The total stock volume and the return are analyzed for a number of stocks. A single button leads to a simple user interface to run analysis on all stocks or clear the worksheet.

![Sample Screenshot](https://github.com/Duvey314/stock-analysis/blob/master/UI%20Screenshot.PNG)

# Challenge

The client wanted a simple way to analyze the provided stock data for their parents. The first attempt used a nested for loop to look through the entire data sheet and find one stock ticker on each pass through. This works but is not very fast and it is hard to add stocks. To speed up the processing, the code was refactored to use arrays to hold the stock tickers, total volume, along with start and end price. This meant that the code only had to run through the data set once. If the client wanted to add other stocks to the analysis, they would simply need to change they tickerNum variable and add the ticker to the tickers array.

The user form was just for some practice for myself.



