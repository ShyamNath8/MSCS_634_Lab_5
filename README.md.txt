Name: Shyam Nath
Course Title: Advanced Big Data and Data Mining(MSCS-634-M40)
Lab Assignment Title: Clustering Techniques Using DBSCAN and Hierarchical Clustering

Purpose
The purpose of this lab is to explore unsupervised learning techniques, specifically Hierarchical Clustering and DBSCAN, using the Wine dataset from the `sklearn.datasets` library. The lab aims to enhance understanding of how clustering algorithms group similar data points, how to evaluate clustering performance, and how parameter choices influence results.

Key Insights

Hierarchical Clustering (Agglomerative):
  - Performed well on the Wine dataset with stable clusters.
  - The dendrogram helped visually identify the optimal number of clusters.
  - Produced meaningful groupings aligned with the known wine classes.

DBSCAN Clustering:
  - Showed sensitivity to `eps` and `min_samples` parameters.
  - Effectively detected outliers, but struggled to find stable clusters with default parameters.
  - Required more tuning and understanding of data density.

Evaluation Metrics:
  - Silhouette Scores were higher for Hierarchical clustering, indicating better-defined clusters.
  - DBSCAN showed lower homogeneity/completeness unless parameters were carefully chosen.

Challenges and Decisions

Parameter Tuning:
  - Choosing the correct number of clusters for Hierarchical Clustering was guided by dendrogram structure.
  - DBSCAN was more challenging due to its reliance on density-based parameters (`eps`, `min_samples`), which needed trial and error.

Visualization:
  - Visualizing high-dimensional data in 2D required selecting meaningful principal components or feature pairs.

Interpretation:
  - Understanding clustering metrics like silhouette score, homogeneity, and completeness helped validate results.

Files Included

`Lab_5_Clustering.ipynb` — Main Jupyter Notebook with all analysis and visualizations.
`README.md` — Summary of the lab, findings, and challenges.

