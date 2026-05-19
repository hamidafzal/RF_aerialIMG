🌍 Aerial Image Classification using Random Forest

This repository implements a machine learning pipeline for aerial image classification using a Random Forest (RF) classifier. The workflow combines texture and morphological feature extraction with dimensionality reduction and feature selection techniques to improve classification performance.

📌 Pipeline Overview

The full pipeline consists of the following stages:

Feature Extraction
Dimensionality Reduction (LDA)
Feature Selection (SFS)
Classification (Random Forest)
🧩 Feature Extraction
🟦 GLCM (Gray-Level Co-occurrence Matrix)

GLCM is used to capture spatial relationships between pixel intensities, enabling extraction of rich texture information from aerial images.

🟩 Textural Features

Texture descriptors are extracted using methods such as:

Haralick features
Gabor filters
Other statistical texture measures
🟨 Morphological Features

Shape- and structure-based features are extracted, including:

Area
Perimeter
Compactness
Shape descriptors
📉 Dimensionality Reduction: LDA

Linear Discriminant Analysis (LDA) is applied to:

Reduce feature dimensionality
Preserve class separability
Improve computational efficiency and model performance
🔍 Feature Selection: SFS

Sequential Feature Selection (SFS) is used to identify the most relevant subset of features by:

Iteratively adding/removing features
Optimizing classification performance
Reducing overfitting and redundancy
🌲 Classification: Random Forest

A Random Forest classifier is trained on the selected features.

Key advantages:

Ensemble of decision trees
Robust to noise and overfitting
High accuracy for high-dimensional data
🚀 Usage

Follow these steps to run the pipeline:

1. Data Preparation
Prepare your aerial image dataset
Extract:
GLCM features
Textural features
Morphological features
2. Dimensionality Reduction (LDA)
Apply LDA on extracted features
3. Feature Selection (SFS)
Run Sequential Feature Selection to identify optimal feature subset
4. Classification (Random Forest)
Train RF model using selected features
Evaluate performance on test data
