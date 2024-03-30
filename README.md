### Classification with Ensemble Learning

This repository contains code for a classification task aimed at achieving a targeted cross entropy loss on an unknown tabular dataset. Various machine learning algorithms, including LightGBM, XGBoost, Multi-Layer Perceptron (MLP), and Random Forest, are utilized individually and as an ensemble to achieve the desired loss below a specified threshold.

#### Approach Overview:

1. **Data Preprocessing:** The UMAP (Uniform Manifold Approximation and Projection) model is used for data preprocessing to extract meaningful, non-linear encodings from the raw tabular data.

2. **Model Training:** Each of the chosen machine learning algorithms is trained on the preprocessed data. 

3. **Ensemble Learning:** The ensemble of models is constructed, and their contributions to the final prediction are determined using Gaussian Process Minimization.

#### Repository Contents:

- `swc_casestudy.ipynb`: This Jupyter notebook encompasses the entire pipeline, including data preprocessing, model training, validation, testing, and ensemble learning steps.

This case study was completed for the hiring process of the company SWC Capital.

