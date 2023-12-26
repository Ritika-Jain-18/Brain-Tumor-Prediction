# Brain-Tumor-Prediction

This project is a two class classification problem where we grade glioma based on the dataset which has 20 mutated genes and 3 clinical features. The prediction task is to determine whether a patient is Lower-Grade Glioma (LGG) or Glioblastoma Multiforme (GBM) with a given clinical and molecular/mutation features.

## Overview

Gliomas are the most common primary brain tumors and can be graded as Lower-Grade Glioma (LGG) or Glioblastoma Multiforme (GBM) based on histological, imaging, clinical, and molecular criteria. Accurate grading is crucial for treatment decisions, but conventional molecular tests are often expensive. The objective is to predict glioma grades using a subset of molecular mutation and clinical features, improving accuracy of prediction while reducing the costs.

## Introduction

Brain Tumor Prediction is a critical application of machine learning in the medical field. Early detection of brain tumors can significantly improve patient outcomes. This project provides a solution for automating the process of tumor detection in brain using some clinical features, assisting healthcare professionals in making timely and accurate diagnoses.

## Features

- Binary classification: Predicts whether a brain tumor is LGG or GBM type.
- User-friendly interface for easy interaction.
- Supports input of clinical and molecular/mutation features for prediction.
- Pre-trained model for quick deployment.
  
## Dataset

The provided data includes training data[1] with 24 features and 775 in-
stances, along with corresponding training data labels and test data. The dataset for this study is extensive, encompassing a comprehensive range of features. These features include demographic information such as age and gender, primary diagnoses, racial background, and the mutation status of various genes. This combination of clinical and molecular data provides a rich foundation for predictive modeling.

## Results

Notably, the classifiers, including Adaptive Boosting, Decision Tree, Random Forest, and Support Vector Machine, achieved exceptionally high precision, recall, and F-measure scores, all exceeding 0.95. These results indicate the models’ ability to accurately classify glioma grades. While Logistic Regression and Naive Bayes exhibited slightly lower but still commendable performance, these findings collectively demonstrate the robustness and effectiveness of the machine learning models in distinguishing between lower-grade glioma (LGG) and glioblastoma multiforme (GBM).

--
