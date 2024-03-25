# CryptoClustering
1. Using the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

2. Creating a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
3. Finding the Best Value for k Using the Original Scaled DataFrame
4. Using the elbow method to find the best value for k using the following steps:

5. Creating a list with the number of k values from 1 to 11.
6. Creating an empty list to store the inertia values.
7. Creating a for loop to compute the inertia with each possible value of k.
8 Creating a dictionary with the data to plot the elbow curve.
9. Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
10. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
11. Using the following steps to cluster the cryptocurrencies for the best value for k on the original scaled data:

12. Initializing the K-means model with the best value for k.
13. Fitting the K-means model using the original scaled DataFrame.
14. Predicting the clusters to group the cryptocurrencies using the original scaled DataFrame.
15. Creating a copy of the original data and add a new column with the predicted clusters.
16. Creating a scatter plot using hvPlot as follows:
17. Settinhg the x-axis as "PC1" and the y-axis as "PC2".
18. Coloring the graph points with the labels found using K-means.
19. Add the "coin_id" column in the hover_cols parameter to identify the cryptocurrency represented by each data point.
20. Optimizing  Clusters with Principal Component Analysis
21. Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

22.Creating a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
23. Finding the Best Value for k Using the PCA Data
24. Using the elbow method on the PCA data to find the best value for k using the following steps:

25. Creating a list with the number of k-values from 1 to 11.
26. Creating  an empty list to store the inertia values.
27. Creating a for loop to compute the inertia with each possible value of k.
28. Creating a dictionary with the data to plot the Elbow curve.
29 Plotting a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
30. Clustring Cryptocurrencies with K-means Using the PCA Data
31. Using the following steps to cluster the cryptocurrencies for the best value for k on the PCA data:

32. Initializing the K-means model with the best value for k.
33. Fittibg the K-means model using the PCA data.
34. Predictuing the clusters to group the cryptocurrencies using the PCA data.
35. Creating a copy of the DataFrame with the PCA data and add a new column to store the predicted clusters.
36. Creating a scatter plot using hvPlot as follows:
37. Setting the x-axis as "price_change_percentage_24h" and the y-axis as "price_change_percentage_7d".
38. Coloring the graph points with the labels found using K-means.
39. Adding the "coin_id" column in the hover_cols parameter to identify the cryptocurrency represented by each data point.
