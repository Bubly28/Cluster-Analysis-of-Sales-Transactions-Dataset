# Cluster-Analysis-of-Sales-Transactions-Dataset
This project focuses on the comparison of two clustering methods, Prototype-based Clustering (using Fuzzy C-means) and K-means Clustering, applied to a weekly sales dataset. The goal is to identify patterns in the data and evaluate the effectiveness of each clustering technique.

Introduction:

The assignment compares prototype-based clustering using the Fuzzy C-means (FCM) algorithm and K-means clustering. These methods are pivotal for uncovering patterns in data without predefined categories. FCM allows data points to belong to multiple clusters, handling complex structures with partial membership. In contrast, K-means assigns each data point to a single cluster, organizing data in a distinct manner. The comparison aims to evaluate the adaptability, readability, sensitivity to outliers, and overall utility of these techniques to guide users in selecting the best approach for their data analysis needs.

Data and Preprocessing:

- Dataset: Weekly sales dataset with quantities for 800 products over 52 weeks.
- Attributes: Each row represents a product, and each column represents a specific week.
- Normalization: The dataset includes normalized data columns and shows weekly fluctuations.
- Preprocessing Steps:
  - Standard scaling of sales data to ensure uniform magnitude.
  - Z-score transformation to identify and adjust outliers.
  - Preparing the dataset for robust clustering analysis.

Cluster Analysis:

- Techniques Used: K-means and Fuzzy C-means (FCM) clustering.
- Prototype-based Clustering (FCM): Allows data points to have partial membership in multiple clusters, addressing inherent ambiguities in the dataset.
- K-means Clustering: Minimizes the sum of squares within each cluster, assigning each data point to a single cluster.
- Rationale: FCM handles ambiguity and intricate customer purchasing patterns, while K-means offers a straightforward and transparent classification of products.

Results:

- Elbow Plot: Used to determine the optimal number of clusters.
- Fuzzy Partition Coefficient (FPC): FCM resulted in an FPC of 0.8952, indicating significant complexity with partial membership across clusters.
- Inertia Value: K-means yielded an inertia value of 10,656.04, suggesting less uncertainty with clear cluster assignments.
- Scatter Plots: Showed comparable patterns between FCM and K-means, indicating consistency in identifying structures.
- Cluster Boundaries: FCM clusters had fuzzy boundaries, while K-means clusters were more distinct.

Conclusion:

- Evaluation Metrics: High Silhouette Score (0.7084) and low Davies-Bouldin Index (0.5549) indicate well-defined and cohesive clusters.
- FCM's Strength: FPC of 0.8952 demonstrates its ability to handle uncertainty.
- Overall: Both methods effectively capture underlying structures in the dataset, with consistent results providing insights into weekly customer purchasing patterns.
