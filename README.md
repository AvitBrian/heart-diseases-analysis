# heart-diseases-analysis
 We're using clusstering for this one.
 
## Best Performance: K-means

- Clear cluster separation in PCA/t-SNE plots
- Well-balanced, distinct clusters in heatmap
- Ideal for medical data's spherical/elliptical distribution
- Computationally efficient and easily interpretable

## Runner-up: GMM

- Similar quality to K-means
- Smoother boundaries
- More complex implementation

## Third: Hierarchical

- Decent separation but less distinct
- Shows outlier sensitivity
- Higher computational cost

## Least Effective: DBSCAN

- Poor separation (most points in one cluster)
- Unsuitable for this data structure

**Conclusion**: K-means - combines best cluster definition, interpretability, and efficiency for medical data analysis. The clear three-cluster separation matches the dendrogram validation and provides meaningful patient subgroups for clinical use.
