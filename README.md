# Spotify_Songs_Clustering

## In this project

Given a dataset of popular songs on Spotify, which contains artists and music names with all audio characteristics of each music.
Goal : To group music genres based on similarities in their audio characteristics.

Dataset can be found here https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset

## Implementation Steps

- Extract the data
- Clean/ Transform the data as required. (In this dataset, before proceeding, we will drop the index column as it is not required)
- Check for the correlation between all the audio features in the dataset.
- Create a new dataset of all the audio characteristics & perform clustering analysis.
  - Use K-means clustering algorithm to find similarities between all the audio features. (K=10, creating 10 clusters)
- Add clusters in the original dataset based on the similarities discovered.
- Visualize the clusters based on some of the audio features.

## About Clustering
Clustering is a machine learning technique to group data points characterized by specific features.

### K-Means Clustering
- Unsupervised Learning algorithm
- Groups unlabeled dataset into different clusters.
- K defines the number of pre-defined clusters that need to be created in the process.
- Divides the unlabeled dataset into k different clusters in such a way that each dataset belongs only one group that has similar properties.
- centroid-based algorithm, where each cluster is associated with a centroid.
- 2 tasks are performed mainly
   - Determinee best value for K center points or centroids by an iterative process.
   - Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.

