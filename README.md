# SP500-Returns-By-Week
S&amp;P 500 Returns by Expiration Week

This code investigates a method of determining which weeks of the year that S&P 500 will be positive or negative based on their historical performance. Significant weeks are then identified as those weeks that have moved in a consistent direction more often than would be expected by chance.  For a dataset of 25 years, that’s 17 or more times. 

Statistical validity is explored by means of Monte Carlo analysis.

The code analyzes data from yahoo finance from 1998 - 2018, calculates weekly returns and performs walk forward analysis to create a backtest.
An equity curve and performance report is created.


