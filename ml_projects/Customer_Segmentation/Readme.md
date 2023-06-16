**What is Customer Segmentation?**

Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.

**Advantages of Customer Segmentation**

* Determine appropriate product pricing.
* Develop customized marketing campaigns.
* Design an optimal distribution strategy.
* Prioritize new product development efforts.

Customer Segmentation is one the most important applications of unsupervised learning. In this machine learning project, we will make use of K-means clustering which is the essential algorithm for clustering unlabeled dataset.

**What is K-Means Clustering?**

K-Means algorithm is an iterative algorithm that tries to partition the dataset into K pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid is at the minimum. The less variation we have within clusters, the more homogeneous the data points are within the same cluster. We then proceeded to perform K-means Clustering which will create different clusters to group similar spending activity based on their age and annual income. KMeans Clustering selects random values from the data and forms clusters assigned. The closest values from the centre of each cluster were taken to update the cluster and reshape the plot (just like k-NN). The closest values are based on Euclidean Distance.


In the first step of this Machine Learning project, we will import all the necessary libraries and then proceed with the data exploration and visualization. Finally, we will review the input data to gain the necessary insights.


**Dependencies:**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Sklearn

**Dataset:**

The dataset is already provided in the folder.

Kaggle Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
