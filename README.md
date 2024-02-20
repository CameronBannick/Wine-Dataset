# Wine Clustering 
## Introduction
Data was gathered for popular wines in hopes of clustering them into groups for a wine delivery service to use to better serve customers with wine recommendations.
## The data
Alcohol              
Malic_Acid            
Ash                   
Ash_Alcanity          
Magnesium              
Total_Phenols        
Flavanoids            
Nonflavanoid_Phenols  
Proanthocyanins       
Color_Intensity       
Hue                   
OD280                 
Proline 
## Cluster Model
Before clustering the data, a principal component analysis was conducted. What this does is keep all the important information and scales it down into less features. This allows the cluster model to run better. We condensed the features in 5 to retain 80% variance. We then went with 3 clusters, as our tests showed it worked best.

## Cluster Analysis

Relationships were found between Alcohol, Malic Acid, Flavanoids, Color_intensity, Hue, and OD280.

![image](https://github.com/CameronBannick/Wine-Dataset/blob/main/Cluster_means.png)
### Alcohol
Cluster 0: Least amount of alcohol on average (12)
Cluster 1: Most amount on average (14)
Cluster 2: Middle amount on average (13)

### Malic Acid
Cluster 0: Lowest amount on average (1.9)
Cluster 1: Middle amount on average (2)
Cluster 2: Most amount on average (3.5)

### Flavanoids
Cluster 0: Middle amount on average (2.1)
Cluster 1: Most amount on average (3)
Cluster 2: Least amount on average (.6)

### Color Intensity
Cluster 0: Least amount on average (3)
Cluster 1: Middle amount on average (5.2)
Cluster 2: Most amount on average (7.2)

### Hue
Cluster 0: Tied for most (1)
Cluster 1: Tied for most(1)
Cluster 2: Least on average (.7)

### OD280
Cluster 0: Middle amount on average (2.7)
Cluster 1: Most amount on average (3.2)
Cluster 2: Least on average (1.6)

## Statistical Analysis
After finding these relationships, we performed several hypothesis tests to see if there was a statistical significance between the features between clusters. The only feature that had a statistical significance was alcohol content.

## Recomendations/Next Steps
Training the model on more data to see if more relationships can be found. Clusters based on alcohol alone might be enough for customers, however consulting a SME for a second opinion might be wise.

