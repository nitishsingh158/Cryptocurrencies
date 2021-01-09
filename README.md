# Analyzing Cryptocurrencies through Unsupervised Machine Learning

![Coins](Resources/coins.png)

### Overview
This project utilizes the unsupervised clustering algorithm to categorise cryptocurrency data from [Crypto Compare](https://www.cryptocompare.com/). The coins are categorized based on the following information:
 - Coin Algorithm
 - Mining Activity
 - Total Mined Coins
 - Total Coins Supply

### Data

Raw data from Crypto Coin

![Coins](Resources/coins1.png)


Data with dummy variables for Algorithm and ProofType 

![Coins](Resources/coins3.png)


Data after using PCA to reduce to 3 features

![Coins](Resources/coins4.png)

Elbow Curve to determine the number of clusters to be used with KMeans

![Coins](Resources/elbow_curve.png)

HVPlot showing the different classes of Coins against the PC1, PC2 and PC3 axis

![Coins](Resources/hvplot.png)

Scatter Plot of the coins according to the clustered classes
![Coins](Resources/scatter_plot.png)


### Summary
The KMeans clustering algorithm was able to segregate the coins based on the basic structural data for each coin. 
Next step: To validate the effectiveness of the clustering, the actual performance of the coins in each class should be measured. 