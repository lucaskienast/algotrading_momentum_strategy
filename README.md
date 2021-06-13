# Algotrading Simple Momentum Strategy
This is a simple momentum trading strategy written in Python. It works as follows:
- load market data 
- resample adjusted prices
- compute log returns
- shift returns
- generate trading signal for best and worst _n_ performers
- compute projected returns
- annualise rate of return
- perform one-sided t-test to see if null hypothesis (mean return is zero) can be rejected
