# portfolio_optimization_mc_simulation

The project looks at a stock portfolio and finds the most optimal weights for each stock using mean-variance optimization, then two different portfolios are looked at: the portfolio with the highest Sharpe ratio and the portfolio with lowest risk. 

These two portfolios are then compared using Monte Carlo simulation. Each portfolio will simulate a random walk for one year in the stock market for 1 year. 
Each portfolio will generate 1000 Monte Carlo (MC) points, where one MC point is the ending balance of the portfolio after holding for 1 year in the stock market.
The initial balance of the portfolio starts at $100,000. 
The performance of each portfolio is evaluated by looking at the mean and standard deviation of the distributions of the 1000 MC points. 
