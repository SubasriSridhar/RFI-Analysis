## RFI Implementation

Cluster the customers with one of the most often used clustering ML algorithm , K-Means. The first step is to find out the value of ‘K’. I have used elbow method to find the K value. The Elbow plot shows at the value of 3 the mean changes drastically and then the graph steadily shows the variation. Therefore, K value is 3. (Coffey, 2016)

![image](https://user-images.githubusercontent.com/34976961/74982651-6ea7b400-542c-11ea-891c-f58a290b6ddc.png)

Figure 52. Finding number of clusters using Elbow method

Following this the Kmeans cluster is built using the Euclidean distance. The 3D rendering of the clusters is helpful when working with three input variables, as an RFI analysis often is. The first graph features planes through each cluster that help the user understand the value associated with the cluster. (Dabakoglu, 2019)

![image](https://user-images.githubusercontent.com/34976961/74982678-7cf5d000-542c-11ea-9717-a1c0b1009e63.png)

Figure 53. K-Means Cluster

 

Visualizing the customer segments is not so clear from the clustering. To explore the results, the cluster image of each variable is plotted to explore the clustering behaviour. (Makhija, 2018)

![image](https://user-images.githubusercontent.com/34976961/74982767-9f87e900-542c-11ea-9715-3304dc13ee09.png)

Figure 54. RFI Analysis Result

 

Looking at the plot above, clearly shows that the user who are recent are in Cluster 1 are recent, frequent players but not intense and the users in Cluster 2 were neither recent nor intense players but they were frequent players, the users in Cluster 3 were neither recent nor frequent but they were intense players. The Cluster 1,2 and 3 can be targeted for promotions and Cluster 0 is not very useful . This can be better explained through the Snake plot and Relative importance: (Urbonas, 2019)

![image](https://user-images.githubusercontent.com/34976961/74982808-ae6e9b80-542c-11ea-8fff-d69c6b673d78.png)   ![image](https://user-images.githubusercontent.com/34976961/74982814-b0d0f580-542c-11ea-89b4-f0ba7c6913b3.png)


Figure 55. Snake Plot                   Figure 56. Relative importance plot RFI

 

 

 

 

 

 
