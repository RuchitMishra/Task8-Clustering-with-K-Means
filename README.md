# Task8-Clustering-with-K-Means
Tools Used Scikit-learn: Clustering, PCA, metrics

Pandas: Data handling

Matplotlib: Visualization

🔁 Steps Overview

Load & Visualize Dataset Used the Iris dataset (you can replace it with any dataset).
Scaled features for uniformity.

Applied PCA to reduce to 2D for plotting.

Fit K-Means Model Applied KMeans(n_clusters=3) to assign clusters.
Labels represent which cluster each data point belongs to.

Elbow Method Ran K-Means for K = 1 to 9.
Plotted inertia (sum of squared distances) to find the "elbow" — best K.

Cluster Visualization Used PCA-transformed 2D features.
Colored each data point by its assigned cluster.

Evaluate with Silhouette Score Higher Silhouette Score (closer to 1) = better clustering.
Evaluated the compactness and separation of clusters.

📊 Example Output A plot of inertia vs K to choose optimal clusters.

A 2D cluster visualization.

A Silhouette Score that reflects clustering quality.
