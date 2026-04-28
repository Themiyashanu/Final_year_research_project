# Final Year Research Project

This repository contains the data preparation and exploratory analysis work for my final year research project, focused on education and health-related indicators in the Uva region (Sri Lanka), using GN-level datasets.

## Project Structure

- `data_raw/`  
  Original input datasets (CSV files).

- `data_processed/`  
  Cleaned/merged datasets and analysis outputs.

- `data_processed/pr1_outputs/`  
  PR1-specific output tables (feature summaries, descriptive stats, correlations, PCA loadings, clustering outputs, etc.).

- `notebooks/`  
  Jupyter notebooks used for data analysis and exploration:
  - `PR1_EDA_Uva_Colab.ipynb`
  - `Uva_Education_Health_Colab.ipynb`

- `maps_qgis/`  
  QGIS boundary-related files used for mapping support.

## Main Files

### Raw Data
- `GN_facility_counts_clean.csv`
- `GN_hospital_school_distances_km.csv`
- `Health and School Counts.csv`
- `gn_crosswalk_final.csv`

### Processed Data
- `UVA_master_dataset_education_health.csv`
- `pr1_outputs/01_feature_summary.csv`
- `pr1_outputs/02_descriptive_statistics.csv`
- `pr1_outputs/03_correlation_matrix.csv`
- `pr1_outputs/04_district_comparison.csv`
- `pr1_outputs/05_kmeans_cluster_summary.csv`
- `pr1_outputs/06_pca_loadings.csv`
- `pr1_outputs/07_correlation_dist_demographics.csv`
- `pr1_outputs/uva_gn_pr1_with_distances.csv`
- `pr1_outputs/uva_gn_pr1_cleaned_with_clusters.csv`

## Objectives

- Integrate education and health related GN-level datasets.
- Perform exploratory data analysis (EDA).
- Generate descriptive and comparative statistics.
- Study relationships using correlation and PCA.
- Identify GN patterns using clustering methods.

## Tools & Environment

- Python (via Jupyter/Colab notebooks)
- CSV-based data processing
- QGIS support files for geospatial context

## Notes

- Some datasets may be large; use Git LFS if needed for very large files.
- Keep sensitive/private data out of the repository.

## Author

Final Year Research Project - 2026
