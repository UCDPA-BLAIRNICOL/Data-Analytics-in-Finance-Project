# Data-Analytics-in-Finance-Project
A repository of commits for my data analytics in finance project at UCD.

This contains the relevant CSVs for the course project as well as the coding project itself. 


To run the project it would be necessary to download the 3 CSV files, then the Final version of the notebook.

The aim of the project is to identify the optimal portfolio, on a risk/return basis, over the past 3 years. We look at benefits of diversification of different asset classes within a portfolio in this project. To ensure we don't need to take any FX calculations or trading holidays into account we use the EurStoxx index to represent equities and we use the IBoxx index to represent bonds. 

The weightings of each of the portfolios are adjusted by 10% each time, to give us 11 model portfolios. The mean returns and standard deviations of the portfolios are calculated. We then take the 3 month German government bond as the risk free rate. Using this we can calculate the Sharpe ratio to give us the optimal portfolio for the sample period when considering risk and return. 
