### Mall Customers Segmentation using K-Means Clustering
In this exercise is performed customer segmentation of a shopping mall using the dataset mall_customers.csv

The available information are:
 - **CustomerID**: identification code of the customer.
 - **Gender**: gender of the customer.
 - **Age**: age of the customer.
 - **Annual Income (k$)**: customer's annual income in $1000.
 - **Spending Score (1-100)**: score assigned to the customer based on spending.

The aim is to create a clustering model using the kmeans algorithm, using the following information:
 1. Age and Spending Score
 2. Annual Income and Spending Score
 3. Age, Annual Income and Spending Score

For each model, the Elbow Method is used to determine the number of clusters and visualized the clusters by a scatterplot. 
The last model is used to associate some customers to a cluster, the result is exported to an EXCEL file called *mall_customers_prediction.xlsx* containing two columns:
 - **CustomerID**: the customer identification code.
 - **Customer Group**: the cluster to which it belongs.
