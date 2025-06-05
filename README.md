# Iris Machine Learning Assessment

---

## Overview

This repository contains a Jupyter notebook implementing **K-Means Clustering** and **Principal Component Analysis (PCA)** from scratch on the Iris dataset, as part of a machine learning assessment. The implementations use Python with **NumPy**, **Pandas**, and **Matplotlib**, adhering to the requirement to avoid libraries with built-in algorithm implementations (e.g., scikit-learn).

---

## Repository Contents

- **`Iris_ML_Assessment.ipynb`**: Jupyter notebook with:
  - Data preprocessing (loading, removing 'Species', standardization).
  - K-Means Clustering implemented from scratch with visualizations (clusters vs. species).
  - PCA implemented from scratch with a 3D scatter plot and eigenvalue analysis.
  - Evaluation of results, including variance explained (PC1: 76.37%, PC2: 18.85%, PC3: 4.79%).
  - Markdown cells explaining preprocessing, algorithms, and results.
- **`Iris Dataset.csv`**: The Iris dataset with measurements for 150 iris flowers (sepal length, sepal width, petal length, petal width, species).

---

## Requirements

- **Python**: Version 3.5 or higher (developed with Python 3.12)
- **Libraries**: 
  - NumPy
  - Pandas
  - Matplotlib
- **Environment**: Jupyter Notebook or JupyterLab to run the `.ipynb` file

---

## Setup and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Iris-ML-Assessment.git


## Install dependencies:
pip install numpy pandas matplotlib


Run the notebook:
jupyter notebook Iris_ML_Assessment.ipynb


Execute all cells to view the code, visualizations, and outputs (plots, eigenvalues, variance explained).


## Notebook Structure

Introduction: Project overview and objectives.
Data Preprocessing: Loading dataset, removing 'Species', checking for missing values, and standardizing features.
K-Means Clustering:
Custom implementation of K-Means with k=3.
Two plots: cluster assignments (with centroids) and actual species.


## Principal Component Analysis (PCA):
Custom implementation of PCA for 3 components.
3D scatter plot of data in the first three principal components.
Eigenvalue and variance explained analysis.


Evaluation: Comparison of K-Means clusters to species and PCA variance analysis.
Conclusion: Summary of findings and potential improvements.

## Key Results

K-Means Clustering:

Clusters align closely with the three Iris species, as shown in the visualizations.
Centroids indicate effective separation, especially for distinct species like Setosa.


PCA:

Variance explained:
Principal Component 1: 76.37%
Principal Component 2: 18.85%
Principal Component 3: 4.79%
Cumulative (PC1 + PC2): 95.21%


The 3D plot shows clear species separation, with minor overlap between Versicolor and Virginica.



## Notes

The repository is public as required for the assessment.
The notebook includes detailed markdown explanations for preprocessing, algorithms, and results, earning potential bonus points for clarity and visualization.
For submission, provide the GitHub repository URL to the assessment portal.
Ensure the notebook is run with all outputs (plots, eigenvalues, variance) saved.

---

**Author:** Saksham Mahajan  
**Date:** June 2025  
**Contact:** sakshammahajan2004@gmail.com

