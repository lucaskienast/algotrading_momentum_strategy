# Algotrading Simple Momentum Strategy
This project is a simple trading strategy and tests to see if it has the potential to be profitable. A universe of stocks and time range is supplied. The signal is computed for the time range given and applied to the dataset to produce projected returns. Finally, a statistical test will be performed on the mean of the returns to conclude if there is alpha in the signal. For the dataset, we'll be using the end of day from Quotemedia.

## Installation
Use `git clone` to get a copy of this repository.
```
$ git clone https://github.com/lucaskienast/algotrading_momentum_strategy.git
$ cd algotrading_momentum_strategy
```

## Method
- load market data 
- resample adjusted prices
- compute log returns
- shift returns
- generate trading signal for best and worst _n_ performers
- compute projected returns
- annualise rate of return
- perform one-sided t-test to see if null hypothesis (mean return is zero) can be rejected

## Results
Mean Daily Return: 0.0032
Standard Error: 0.0022
Annualized Rate of Return: 3.98%
