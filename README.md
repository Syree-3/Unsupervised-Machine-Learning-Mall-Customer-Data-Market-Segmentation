Here is a summary of the key steps for customer segmentation using K-means clustering and PCA on the provided mall customer data:

**Importing Libraries**
Imported NumPy, Pandas, Matplotlib, LabelEncoder, StandardScaler, KMeans, and PCA.

**Data Preprocessing**
Loaded the dataset and dropped the CustomerID column. Encoded the gender data to numeric values using LabelEncoder. Scaled the features using StandardScaler.

**Clustering with K-Means**
Determined optimal number of clusters using the elbow method. Clustered data into 10 clusters using K-Means.

**Visualising with PCA**
Reduced dimensions to 2 principal components using PCA. Plotted a scatter plot with each cluster colored differently. Marked the cluster centroids.

**Key Insights**
Data segmented into 10 distinct customer groups based on age, income, gender and spending score.
PCA visualisation shows distinct clusters with minimal overlap.
Centroids can be analysed to understand key features of each cluster.
This segmentation allows for targeted marketing based on customer preferences of each group.

