# Product Variety Clustering — Elsa.Science

Consulting project for **Elsa.Science** (Swedish EdTech, now closed). Applied unsupervised clustering to segment and profile product varieties from normalised feature data.

## Approach

- Compared **K-Means** and **agglomerative hierarchical clustering**
- Determined optimal cluster count via the **elbow method** (inertia curve) and **silhouette scores**
- Profiled each cluster to identify distinct product groupings and support product strategy decisions

## Data

Three datasets (`norm_data.csv`, `norm_df.csv`, `varieties.csv`) — normalised feature vectors derived from internal Elsa.Science product data.

## Stack

scikit-learn · pandas · NumPy · matplotlib · seaborn
