# Customer-Segmentation
Clustering customers on the their purchase behaviour 
Introduction:
The Wholesale Dataset provides information on the annual spending on different categories of products for clients of a wholesale distributor. The dataset includes data for two channels of clients (Horeca and Retail) and three regions.

Objective:
The objective of this project is to perform exploratory data analysis (EDA) and clustering on the Wholesale Dataset to understand the underlying patterns and characteristics of the data.

Approach:

Data Preprocessing: The dataset was first cleaned and preprocessed to remove any missing or duplicated values and to treat outliers.
Exploratory Data Analysis (EDA): The EDA was performed to compare the spending habits of the two channels for different regions and to identify correlations between the different features using a correlation matrix.
Clustering:
a. Clustering on the basis of Region: PCA was first applied to the data to reduce it to 2 dimensions and then an elbow diagram was used to determine the optimal number of clusters. The silhouete score was used to evaluate the performance of the clusters.
b. Clustering on the basis of Channel: The same approach was used for clustering on the basis of channel as was used for clustering on the basis of region. However, the silhouete score was better for channel than for region.
c. DBSCAN Algorithm: DBSCAN algorithm was applied on the whole dataset after dealing with outliers and without reducing dimensions. Hyperparameter tuning was performed to determine the optimal number of clusters. However, the silhouete score obtained was only 0.32.
Who can benefit:
This project can be useful for wholesalers, distributors, and retailers who want to gain insights into the spending habits of different regions and channels. The results of the clustering can help these businesses to optimize their supply chain and inventory management strategies.

Conclusion:
The Wholesale Dataset was explored and analyzed using various techniques, including EDA and clustering. The results showed that there were underlying patterns and characteristics in the data that could be useful for businesses in the wholesale and retail industries.


Summary of Analysis and Usage Instructions
The code in the Jupyter Notebook can be used as a starting point for further exploration of the wholesale dataset or for similar datasets in the future.
The analysis and insights presented in the notebook can be used by retailers and wholesalers to understand the spending habits of their customers and make informed decisions about product offerings and marketing strategies.
Researchers and students in the field of machine learning and data science can also use the notebook as a reference for clustering techniques and visualization methods.
The code and analysis in the notebook can be modified and extended to incorporate additional features and techniques as needed for specific projects.
It is important to note that the results and insights presented in the notebook are based on the wholesale dataset used and may not necessarily generalize to other datasets or populations. Therefore, caution should be exercised when applying the findings to other contexts.
