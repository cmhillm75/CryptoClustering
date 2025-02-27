# CryptoClustering

Module 19 Challenge

## Conclusion

Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

Answer: Ther PCA plot is tightly grouped to the negative side of x=0, y=2. theta-token, celsisu-degree-token and ethlend being the furthest from the group all outliers to the postive. For our standard clusters of pricing, the 0 group have the largest spread, 2 clusters have the highest 7 day price change. In comparing the PCA, we have much tighter configuration of our data so we may be losing some dimensionality due to the reduction in components. Overall if determining accoracy of price changes, kmeans=4 provides greater accuracy.

## Specific coin_id = ethlend

PCA Scatter Plot:
PCA1 = 8.089 and PCA2 = -3.897 principal component values for ethlend are the position of the cryptocurrency in the PCA-transformed feature space.

PCA reduces the dimensionality of the data by transforming the original features into a new set of orthogonal (uncorrelated) features called principal components. In this context, PCA1 and PCA2 capture the most significant variance in the data.

Standard Scatter Plot:
price_change_percentage_24h = -4.981 and price_change_percentage_7d = -4.581e-2 are the percentage changes in the price of the cryptocurrency over the last 24 hours and the last 7 days, respectively.

These values are from the standard scatter plot and provide a direct measure of the price movement of the cryptocurrency over different time periods.

What This Means:
PCA Values: The PCA1 and PCA2 values indicate where this cryptocurrency is located in the reduced dimensional space. A higher value for PCA1 suggests that this coin has characteristics that significantly contribute to the variance captured by the first principal component. Similarly, PCA2 indicates its contribution to the second principal component.

Price Change Values: The negative values for price_change_percentage_24h and price_change_percentage_7d indicate that the cryptocurrency's price has decreased over the last 24 hours and 7 days, respectively.

Conclusion:
The PCA values provide a high-level summary of the cryptocurrency's features in the transformed space, helping to identify patterns and clusters.

The price change percentages give specific insights into the recent performance of the cryptocurrency.

Combining Both: If you notice similar PCA values and price change percentages for different cryptocurrencies, it might indicate that these cryptocurrencies exhibit similar patterns in both their feature space and price movement.

In summary, the PCA values tell you about the overall feature-based grouping of the cryptocurrency, while the price change percentages provide detailed information about its recent market performance. Both perspectives together offer a comprehensive understanding of the cryptocurrency's behavior.

## Theta Token

Interpretation:
Moderate Positive PCA1: The cryptocurrency has a moderate association with the primary features that contribute to the first principal component. It means that the cryptocurrency shares common characteristics with other cryptocurrencies that heavily influence PCA1.

Minimal Negative PCA2: The cryptocurrency has a very small negative association with the features that contribute to the second principal component. This means that the features captured in PCA2 are not significant for this cryptocurrency.

Combined Understanding:
The combined PCA values show that this cryptocurrency is primarily influenced by the features captured in PCA1 and has very little influence from the features captured in PCA2.

In the context of the scatter plot, this cryptocurrency would be positioned moderately far along the PCA1 axis and very close to the origin along the PCA2 axis.
