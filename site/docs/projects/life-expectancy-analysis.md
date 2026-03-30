# Life Expectancy Analysis

Source folder: `Life-Expendancy-Analysis/`

## Summary

Project focused on WHO life expectancy data, combining data cleaning, exploratory analysis, clustering, and dimensionality reduction.

## Analysis Used

- Initial and full cleaning steps, including country-name standardization.
- Country ISO mapping for geographic visualization support.
- Missingness audits with nullity inspection and imputation workflows.
- Feature preparation and scaling with `StandardScaler`.
- Clustering with `KMeans`, with `silhouette_score` checks.
- World-map choropleth visualization of cluster assignments.
- Covariance/correlation exploration and PCA for reduced-dimensional structure.
- Additional classification checks with confusion matrix/report outputs.

## Technologies and Methods

- Python, Jupyter Notebook
- `pandas`, `numpy`
- `missingno`, `pycountry`
- `scikit-learn` (`StandardScaler`, `KMeans`, `PCA`, `RandomForestClassifier`, model metrics)
- `plotly` (graph objects + express), `matplotlib`
