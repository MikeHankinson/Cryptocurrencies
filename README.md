# Cryptocurrencies

## Objective
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Analysis Technique
1. Data selection and processing
2. Standardize features using StandardScaler library
3. Use PCA to reduce the number of features
4. Apply dimensionality reduction on the scaled dataset
5. Transform resulting PRINCIPAL COMPONENTS to a DataFrame to fit K-Means
6. Use explained_variance_ratio to learn how much information can be attributed to each principal component
7. Use the elbow curve with the generated principal components to determine K-Value (number of clusters within a dataset)
8. Use the PRINCIPAL COMPONENTS data with the K-means algorithm with the proper value of clusters (K)
9. Plot the Curves to verify number of clusters (K)
