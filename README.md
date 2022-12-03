# Module3Challenge
Analyzing historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. 
# Technologies
- python 3.9.12
- JupyterLab
- libraries: pandas, pathlib, matplotlib
- Windows
# Analysis report
Timeframe for this analysis is set between 2018-01-01 00:00:00 and 2018-03-31 23:59:00. To emphasize early, middle, and later period in the dataset I chose three different dates:
- Jan 16, 2018
- Feb 24, 2018
- Mar 25, 2018

### Arbitrage spread calculation results proved following:
1. Arbitrage spread - Early in the dataset <br /> <br />
count    1419.000000<br />
mean       23.212135<br />
std        67.789186<br />
min      -275.920000<br />
25%        -8.330000<br />
50%        22.280000<br />
75%        52.355000<br />
max       606.800000<br /><br />
Now, we know that 1419 data points exist, that the average difference between the two prices is $23.21, and that the maximum difference is $606.78. The minimum value, -275, tells us that a time existed when Bitstamp had a higher selling price than Coinbase.<br /><br />
2. Arbitrage spread - Middle in the dataset <br /><br />
count    1437.000000<br />
mean        3.396131<br />
std        22.969472<br />
min       -50.180000<br />
25%       -10.590000<br />
50%        -0.010000<br />
75%        12.120000<br />
max       121.320000<br /><br />
Now, we know that 1437 data points exist, that the average difference between the two prices is $3.40, and that the maximum difference is $121.32. The minimum value, -50, tells us that a time existed when Bitstamp had a higher selling price than Coinbase.<br /><br />
3. Arbitrage spread - Later in the dataset<br /> <br />
count    1404.000000<br />
mean       -2.294423<br />
std         9.853020<br />
min       -34.640000<br />
25%        -8.810000<br />
50%        -2.805000<br />
75%         3.767500<br />
max        53.940000<br /><br />
Now, we know that 1404 data points exist, that the average difference between the two prices is $-2.29, and that the maximum difference is $53.94. The minimum value, -34, tells us that a time existed when Bitstamp had a higher selling price than Coinbase. Not a great piece of the review, which as shows later won't be of any profit.<br /> <br />

### After narrowing down the trading opportunities, the results showed following:<br />
<b>Early</b> in the dataset there were many great opportunities to sell/buy the coins. Profit per day turned out to be $14147.1699. <br />
In the <b>middle</b> dates (Feb 24, 2018 to be exact) there were only three opportunities for arbitrage trading. <br /><br />
2018-02-24 08:32:00    121.32<br />
2018-02-24 09:32:00    107.00<br />
2018-02-24 09:39:00    101.75<br /><br />
Total profit per day is $330.0699.<br />
<b>Later</b> in the dataset there were no opportunities for trading. I did the analysis anyway, so different data could be processed later. 
