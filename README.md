## RFI Implementation

Cluster the customers with one of the most often used clustering ML algorithm , K-Means. The first step is to find out the value of ‘K’. I have used elbow method to find the K value. The Elbow plot shows at the value of 3 the mean changes drastically and then the graph steadily shows the variation. Therefore, K value is 3. (Coffey, 2016)

![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

Figure 52. Finding number of clusters using Elbow method

Following this the Kmeans cluster is built using the Euclidean distance. The 3D rendering of the clusters is helpful when working with three input variables, as an RFI analysis often is. The first graph features planes through each cluster that help the user understand the value associated with the cluster. (Dabakoglu, 2019)

![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

Figure 53. K-Means Cluster

 

Visualizing the customer segments is not so clear from the clustering. To explore the results, the cluster image of each variable is plotted to explore the clustering behaviour. (Makhija, 2018)

![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)  ![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg) ![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image010.jpg)

Figure 54. RFI Analysis Result

 

Looking at the plot above, clearly shows that the user who are recent are in Cluster 1 are recent, frequent players but not intense and the users in Cluster 2 were neither recent nor intense players but they were frequent players, the users in Cluster 3 were neither recent nor frequent but they were intense players. The Cluster 1,2 and 3 can be targeted for promotions and Cluster 0 is not very useful . This can be better explained through the Snake plot and Relative importance: (Urbonas, 2019)

![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image012.jpg)   ![img](file:///C:/Users/91979/AppData/Local/Temp/msohtmlclip1/01/clip_image014.jpg)

Figure 55. Snake Plot                   Figure 56. Relative importance plot RFI

 

 

 

 

 

 