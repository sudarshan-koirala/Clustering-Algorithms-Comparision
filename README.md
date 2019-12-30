# Clustering-Algorithms-Comparision

Using K-Means Clustering and Hierarchical clustering on same dataset and comparing the prediction

## Business Problem

Suppose a shopping mall have information about their customers through loyalty cards and want to group them according to their frequent visit and spending to target specific ads for that clusters of customers.

## Dataset

Dataset consists the CustomerID, their gender, age, annual income and spending score. The spending score is calculated by the mall based on their visit to the mall and spending.

## Solution

Only the annual income and spending score is taken in consideration for solving the problem. Two clustering algorithm (K-means and Hierarchical clustering) are used to figure out the clusters and visualize the different prediction made by each algorithm.

The elbow method is used to calculate the number of clusters in K-means and dendogram is used for hierarchical clustering. From both the methods, the number of clusters is found to be 5 which is visualized below.

![Elbow method](https://user-images.githubusercontent.com/14214659/71561802-2ac7ac80-2a84-11ea-988b-febbcb83297a.png)

![Dendogram](https://user-images.githubusercontent.com/14214659/71573746-115b4a80-2aee-11ea-9926-3c241929b250.png)

After knowing the clusters, the data is then fitted into the the respected algorithm. This is how the clusters by both of the models looks like.

![kmeans clusters](https://user-images.githubusercontent.com/14214659/71574431-5634b080-2af1-11ea-9bb1-3a2368cf3fec.png)

![hc clusters](https://user-images.githubusercontent.com/14214659/71573762-1d470c80-2aee-11ea-9e91-4adb5eda07e9.png)

## Conclusion

Both the algorithm finds the same no. of clusters and almost same predictions of observations in the clusters. But apart from this small dataset, HC is not that good for big dataset whereas k-means works fine for any dataset.
