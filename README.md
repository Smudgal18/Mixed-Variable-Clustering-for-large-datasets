# Mixed-Variable-Clustering-for-large-datasets
This R code contains step by step details of how to carry out clustering on data containing both continuous and categorical variables. I have first used gower distance to create distance matrix of the dataset. 

Now, creating this matrix for a big dataset is memory intensive and so I first took a random sample of the data and used that for clustering. I then used k prototypes for carrying out the clustering. After the clusters were created on the sample and after checking the quality of the clustering using Silhoutte coefficient, I assigned cluster labels to the remaining datapoints by calculating their distance from the cluster centres.
