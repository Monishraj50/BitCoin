# BitCoin 
## Prophet
Prophet is a facebooks’ open source time series prediction. Prophet decomposes time series into trend, seasonality and holiday. It has intuitive hyper parameters which are easy to tune.
* Trend models non periodic changes in the value of the time series.</br>
* Seasonality is the periodic changes like daily, weekly, or yearly seasonality.</br>
* Holiday effect which occur on irregular schedules over a day or a period of days.</br>
* Error terms is what is not explained by the model.</br>

### Advantages of using Prophet
* Accommodates seasonality with multiple periods
* Prophet is resilient to missing values
* Best way to handle outliers in Prophet is to remove them
* Fitting of the model is fast
* Intuitive hyper parameters which are easy to tune


### Installing Prophet
Install Prophet using either command prompt or Anaconda prompt using pip


We can also install plotly for plotting the data for prophet



### Steps for using Prophet:
* Make sure you replace closing price for y and date for ds.
* Fit that dataframe to Prophet in order to detect future patterns.
* Predict the upper and lower prices of the closing price.

# Technical Analysis
The basic technical concepts when dealing with stock investing. This are simple theories however, we shouldn't solely rely on these concepts to maximize profits as it is the case with patterns related to moving averages. Before going into this concepts, I will like to show how OHLC and Candlesticks are interpreted.
## OHLC(Open High Low Close) Charts:
The OHLC chart (for open, high, low and close) is a style of financial chart describing open, high, low and close values for a given x coordinate (most likely time). The tip of the lines represent the low and high values and the horizontal segments represent the open and close values. Sample points where the close value is higher (lower) then the open value are called increasing (decreasing).

<img src=https://github.com/Monishraj50/BitCoin/blob/master/img/OHLC.png height =300>
The candle shows the Open price ,the High and Low price and the for each period of time.This differs slightly on wether the candle is Bullish(Up) or Bearish(Down).

## Candlestick Charts:
The candlestick chart is a style of financial chart describing open, high, low and close for a given x coordinate (most likely time). The boxes represent the spread between the open and close values and the lines represent the spread between the low and high values. Sample points where the close value is higher (lower) then the open value are called increasing (decreasing).
<img src=https://github.com/Monishraj50/BitCoin/blob/master/img/CandleStick.png height =300>
## Moving Average:
A moving average (MA) is a stock indicator that is commonly used in technical analysis. A moving average (MA) is a calculation that takes the arithmetic mean of a given set of prices over the specific number of days in the past. The reason for calculating the moving average of a stock is to help smooth out the price data by creating a constantly updated average price.
<img src=https://github.com/Monishraj50/BitCoin/blob/master/img/MovingAvg.png height =300>
