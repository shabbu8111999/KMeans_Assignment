# KMeans_Assignment

## Dataset

The dataset contains fish physical measurements such as length, weight, and weight-to-length ratio. These numerical values are used to group similar fishes.
Dataset Link :- https://www.kaggle.com/datasets/taweilo/fish-species-sampling-weight-and-height-data

---

## Steps Used

- Loaded the dataset and checked for missing values.
- Selected numerical features for clustering.
- Scaled the data using StandardScaler.
- Used the Elbow Method to find the best number of clusters.
- Applied K-Means clustering.
- Visualized the clusters using a scatter plot.

---

## Elbow Method Result

The elbow curve showed a clear bend at K = 3, indicating that 3 clusters is the optimal choice.

---

## Clustering Result

K-Means successfully divided the data into 3 distinct clusters, representing small, medium, and large fishes based on their measurements.

---

## Visualization (Length vs Weight)

- The scatter plot shows clear separation between clusters.
- The yellow colored points represent fishes with smaller length and lower weight.
- The green colored points represent fishes with medium length and weight.
- The purple colored points represent fishes with larger length and higher weight.

---

## Visualization (Weight vs Ratio)

- The scatter plot shows clustering between the second and third scaled features.
- The yellow colored points represent fishes with higher weight and higher weight-to-length ratio.
- The green colored points represent fishes with medium values.
- The purple colored points represent fishes with clearly larger measurements.
