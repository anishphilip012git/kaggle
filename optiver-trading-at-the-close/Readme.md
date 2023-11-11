Learnings: Major learning: Worked on time series data to identify and predict pattern in stock market price in auction  at the time of close

Key python learning: The dataset was considerably large, so had to test a variety of techniques for faster computation.

I tried parallel processing in python for data frames and broadcasting methods for numpys.

1. Identified an interesting way to find the distance between data points in a time interval.
2. Used this to get correlation matrix in a unique way(Sorted Correlation Matrix)
3. Performed permuatation test to identify pairwise correlation of stocks to idnetify highly correlated stocks
4. calculated the correlation matrix and used it to cluster stocks based on cluster correlation matrix
5. Employed Kmeans for clustering stocks

Models applied for predicting stock price --
Linear regression ==
Random Forest ==  
Ensemble method: Gradient Boost Regression Method—couldn't apply because of the large size of data 
                  Even after reducing data set size and max depth of tree th emodel sseemd to be facing lags onmy machine 


Best model : Random Forest Regression Method
