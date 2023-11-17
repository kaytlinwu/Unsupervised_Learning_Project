# machine_learning_project-unsupervised-learning

## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

### Duration:
Approximately 1 hour and 40 minutes

### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:
-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.
The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

### EDA

- Data in numerical columns: 'Fresh', 'Milk', 'Grocery', 'Frozen', 'Detergents_Paper' and 'Delicassan' are bimodal, left-tailed and skewed to the right. 
- Outliers were identified and replaced with the median value through median imputation. Additionally the data was scaled using standard scalar. 
- There is a strong linear correlation between the variables 'Grocery' and 'Detergents_Paper' with a correlation of 0.84. EDA suggests that these variables are positively correlated to each other. 

### KMeans Clustering

- Elbow method was performed and the optimal number of clusters was found to be 6. 
- KMeans model was performed using 6 clusters. Results were plotted on 2 dimensions using PCA component 1 and PCA component 2.
- 6 distinct clusters can be seen through the KMeans model. Overlap between cluster 1 (orange) and cluster 3 (red) can be seen. As plot is 2 dimensional, separation may occur past the 2nd dimension.
- Overall KMeans clustering using 6 clusters represents the data well.

### Hierarchical Clustering

- Dendrogram was performed and the optimal number of clusterse was found to be 6.
- Hierachical Clustering was also plotted on 2 dimensions using PCA component 1 and PCA component 2.
- Compared to KMean, less distinct clusters are seen with hierarchical clustering. Clusters have more overlap between each other. 

### PCA Analysis
- PCA analysis found that the first principal component contained 41% of the variance and the second principal component contained 17% of the variance. Together, these two components accounted for 58% of the variance.

## Conclusion/Further Directions
- Wholesale data can be clustered into 6 distinct clusters. These clusters can be useful in grouping customer spending data and understanding customer yearly spending.
- KMeans model performed better at forming distinct clusters compared to the Hierachical model.
- Other clustering models could be explored in order to find which model best suits the data. 
