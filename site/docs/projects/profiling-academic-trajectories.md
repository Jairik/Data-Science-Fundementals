# Profiling Academic Trajectories

Source folder: `Profiling-Academic-Trajectories/`

## Summary

Capstone project exploring the UCI higher-education student performance dataset. The notebook covers end-to-end exploration, clustering, supervised prediction, and model interpretability.

## Analysis Used

- Programmatic dataset loading and codebook-assisted decoding of categorical labels.
- Data exploration and wrangling for demographic, socioeconomic, and academic variables.
- Unsupervised profiling with `KMeans` and `DBSCAN`, with `silhouette_score` for quality checks.
- Classification of grade/GPA outcomes using `RandomForestClassifier` with `train_test_split`.
- Hyperparameter tuning via `RandomizedSearchCV`.
- Statistical testing (`mannwhitneyu`) for selected social indicators.
- Model explainability using permutation importance and SHAP.

## Technologies and Methods

- Python, Jupyter Notebook
- `pandas`, `numpy`, `scipy`
- `scikit-learn` (`KMeans`, `DBSCAN`, `RandomForestClassifier`, `RandomizedSearchCV`, evaluation metrics)
- `plotly.express`, `matplotlib`
- `shap`
- `ucimlrepo`
