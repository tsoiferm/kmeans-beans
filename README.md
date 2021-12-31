# K-Means Clustering Algorithm on Dry Bean Dataset

I applied the k-means clustering algorithm on a dataset consisting of several features of different dry bean types. I used principal component analysis to reduce the dimensionality of the dataset in order to be able to visualize the data, specifically to analyze the clusters. I determined the approprate number of clusters for this dataset using the elbow method, and to provide further confidence in the chosen number of clusters, I also calculated the silhouette score for n clusters, with n = 2,3,4,5,6,7,8,9,10,11,12,13,14,15. I created silhouette plots for n = 2,3,4,5. 

## Citations
Dry Bean Dataset: 
Murat KOKLU and ILKER ALI OZKAN
KOKLU, M. and OZKAN, I.A., (2020), "Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques." Computers and Electronics in Agriculture, 174, 105507. DOI: https://doi.org/10.1016/j.compag.2020.105507

Code based on tutorial from:
https://www.youtube.com/watch?v=EItlUEPCIzM

Silhouette Score/Visualization:
https://dzone.com/articles/kmeans-silhouette-score-explained-with-python-exam
https://medium.com/mlearning-ai/elbow-method-vs-silhouette-co-efficient-in-determining-the-number-of-clusters-33baff2fbeee
