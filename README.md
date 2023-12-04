# Dynamic_Portfolio_Optimization
1. This paper introduces the Normal Boundary Intersection (NBI) method for highly accurate Pareto frontier prediction in multicriteria optimization as compared to the traditional Weighted Sum Scalarization technique.
2.  It presents dynamic portfolio optimization, highlighting its advantages over static methods in finance.
3.  It states the mean-variance Portfolio model and introduces a new systematic procedure employing NBI for dynamic portfolio optimization through strategic asset reallocation.
4.  Additionally, it showcases empirical analysis using curve fitting techniques to predict future stock prices by defining a polynomial function that can predict the price of a stock given any time in the future.

There are 3 notebooks:
1. NBI_optimization: this introduces the cocept of the NBI method and compares it with the traditional Weighted Sum Scalarization with the help of an optimizaation problem.
2. Portfolio_Optimization_NBI: This is the code to the dynamic portfolio allocation strategy using NBI method reciprocated on 3 stocks of the NIFTY 50.
3. StockPricePrediction_Regression: Uses curve-fitting techniques to predict stock prices. In the code, I have used a 3-degree polynomial and a 10-degree polynomial and found the optimal parameters for the best-fitting curve.
