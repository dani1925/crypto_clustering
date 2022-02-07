# Supervised Machine Learning

It is called supervised learning because the process of an algorithm learning from the training dataset can be thought of as a teacher supervising the learning process. We know the correct answers, the algorithm iteratively makes predictions on the training data and is corrected by the teacher. Learning stops when the algorithm achieves an acceptable level of performance.

In this repository, the data of a data set that contains information on cryptocurrencies will be cleaned with the aim of making clusters with the different cryptos.

## ELBOW CURVE
A fundamental step for any unsupervised algorithm is to determine the optimal number of clusters into which the data may be clustered. The Elbow Method is one of the most popular methods to determine this optimal value of k.

![alt text](https://github.com/dani1925/crypto_clustering/blob/master/resources/plot1.png)

the k means do not show a large difference between 4 and 10 clusters. therefore it is recommended to use 4 clusters.


![alt text](https://github.com/dani1925/crypto_clustering/blob/master/resources/plot2.png)

In the previous image it can be shown how the clustering of the data was carried out, using the pca to reduce the size of the independent variables to 3.

![alt text](https://github.com/dani1925/crypto_clustering/blob/master/resources/plot3.png)