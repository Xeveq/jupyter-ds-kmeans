# jupyter-ds-kmeans
k-means clustering implematiation of iris data set (iris petals):

![image](https://user-images.githubusercontent.com/108526552/177139368-81551fb5-71f1-41aa-b41f-abc94743b169.png)

Next, there are three starting points randomly assigned:

![image](https://user-images.githubusercontent.com/108526552/177139567-1c7d1375-82e7-4814-97ab-b8ff7d03a241.png)

Within a while loop each petal data point is calculating euclidean distance to each starting point, and then chooses the nearest one:

![image](https://user-images.githubusercontent.com/108526552/177139989-618c51a9-9102-4a2f-8a3d-572d8f9144db.png)

within the loop, for each cluster, new centroids coordinates are calculated, and petals are assigned again.
The loop ends when the centriods stops moving, the last iteration outcome shows clustered data:

![image](https://user-images.githubusercontent.com/108526552/177140787-000deaf5-3da3-4c11-a587-f6f8f35f9cf2.png)
