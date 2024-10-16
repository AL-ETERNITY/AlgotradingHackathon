# AlgotradingHackathon
This is my final submission strategy which i developed for the interiit bootcamp algotrading hackathon. 
So, Initially i used over more than 50 combinations to develope a good strategy but in some startegy either my no. of trades would remain very less like 1 or 2 which has no point and in some strategies i got good no. of of trades but my return was very poor than the market return. 
with each strategy i also checked it with each and every time frame of candlestick which was provided and out of them every time i got the best results from 30min timeframes candlestick dataset . So surely i used this dataset in my final strategy,
the final strategy which i developed was using ema and sma crossover with MACD 
## Outcome
From this strategy I got :
Return [%] - 460.461843,
Buy & Hold Return [%] - 216.860216,
profit factor-2.06,
winning rate - 55%,
sharpe ratio - 0.58,
sortino ratio - 1.52,
max drawdown - (-60%),
Other results you can find in my code 
## requirements
pip install pandas, talib and backtesting 
