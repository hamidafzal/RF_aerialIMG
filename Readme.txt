# Aerial Image Classification using Random Forest (RF)

This repository contains code and resources for classifying aerial images using Random Forest (RF) algorithm. The classification process involves data preparation steps such as GLCM (Gray-Level Co-occurrence Matrix), textural feature extraction, and morphological feature extraction. Additionally, Linear Discriminant Analysis (LDA) is calculated to reduce dimensionality, Sequential Feature Selection (SFS) is applied for feature selection, and finally, RF classifier is utilized for image classification.

## Data Preparation

The data preparation stage includes the following steps:

1. **GLCM (Gray-Level Co-occurrence Matrix)**: Calculating GLCM to capture spatial relationships in the image, which helps in extracting texture features.

2. **Textural Feature Extraction**: Extracting texture features from the images using various methods such as Haralick features, Gabor filters, etc.

3. **Morphological Feature Extraction**: Extracting morphological features such as area, perimeter, and shape descriptors from the images.

## Linear Discriminant Analysis (LDA)

LDA is performed to reduce the dimensionality of the feature space while preserving the class discriminatory information.

## Sequential Feature Selection (SFS)

Sequential Feature Selection is applied to select the most relevant features from the feature space. This step helps in improving classification performance by eliminating irrelevant features and reducing overfitting.

## Random Forest (RF) Classification

Random Forest classifier is applied to classify the aerial images based on the selected features. RF is an ensemble learning method that builds multiple decision trees and merges their predictions to improve accuracy and robustness.

## Usage

To use the code provided in this repository, follow these steps:

1. **Data Preparation**: Prepare your aerial images dataset and extract GLCM, textural, and morphological features using the provided scripts or your own methods.

2. **Linear Discriminant Analysis (LDA)**: Calculate LDA using the extracted features to reduce dimensionality.

3. **Sequential Feature Selection (SFS)**: Apply SFS to select the most relevant features.

4. **Random Forest Classification**: Train the RF classifier using the selected features and evaluate its performance on the test dataset.

## Repository Structure

