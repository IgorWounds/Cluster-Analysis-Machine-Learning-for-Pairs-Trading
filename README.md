# Cluster-Analysis-Machine-Learning-for-Pairs-Trading
Algotrading101 blog

What trading assets work the best together to form a trading pair for the Pairs Trading strategy?

Pairs trading is a strategy in which a trader buys one asset while shorting another. The main premise of the trade is that when the two pairs diverge, they will likely converge again resulting in profit for the trader.

I categorized this problem as a clustering unsupervised machine learning task.

The structure of the code and the problem-solving is made up of the following steps:

1. Obtain all the S&P 500 stock from Yahoo Finance
2. Clean and prepare the data (treat missing values, calculate volatility, scale the date, etc.)
3. Fit three Machine Learning Models to the data and explore their outputs
  a) k-Means Clustering
  b) Hierarchical Clustering
  c) Affinity Propagation Clustering
4. Compare the models by their silhouette score and pick the best one
6. Extract the Trading Pairs
  a) Do a cointegration test on clusters to find the best pairs
  b) Plot the Pairs

For a more detailed Guide behind the process please visit the Algotrading101 blog post: https://algotrading101.com/learn/cluster-analysis-guide/

![download (6)](https://user-images.githubusercontent.com/74266147/112733578-0dacb280-8f41-11eb-91ac-456f8245d065.png)

