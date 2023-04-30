## Module-19-Challenge

## Description

### Use knowledge of python and unsupervised learning to predict if Cryptocurrencies are affected by 24-hour or 7-day price changes.

### Technologies used

 - Python notebook

## Getting Started

Open the following file <Crypto_Clustering.ipynb>
1. The <crypto_market_data.csv> was loaded in as a Pandas DataFrame called df_market_data.

2. This data was normalised using the StandardScaler() module from scikit-learn and a DataFrame called df_market_data_scaled, was created with the scaled data. 

3. The elbow method was then used to find the best value for k for the scaled data. 
 - Questions answered in a markdown block.
 - The scaled data was plotted as a scatter plot using the predicted cluster groups, with x="price_change_percentage_24h" and y="price_change_percentage_7d".

3. The scaled data was reduced to 3 principal components with a Principal Component Analysis.
 - The elbow method was then used to find the best value for k for the PCA data.
 - Questions answered in a markdown block.
 - The PCA data was plotted as a scatter plot using the predicted cluster groups.

4. Composite plote for the elbow plot and scatter plots were created to visualise and compare the data.
 -  - Questions answered in a markdown block.

### Enjoy marking!
### Sandra
