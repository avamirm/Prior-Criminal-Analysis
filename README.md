# COMPAS Analysis: Defendant Risk Assessment Dataset

## Overview

The **Correctional Offender Management Profiling for Alternative Sanctions (COMPAS)** algorithm is a widely used commercial tool that predicts the likelihood of criminal defendants re-offending (recidivism). It assists judges and parole officers by categorizing defendants into high, medium, or low-risk groups based on various factors. This project conducts a comprehensive analysis of COMPAS results, focusing on the algorithm's fairness and accuracy in predicting recidivism.

## Objectives

- **Data Exploration**: Understand the dataset structure, key features, and potential biases.
- **Feature Engineering**: Enhance the dataset to improve model performance.
- **Model Training**: Assess the COMPAS algorithm's reliability using five different predictive models.

## Methodology

### Data Preparation

- **Feature Engineering**: Various feature engineering techniques were applied to enhance the dataset's quality.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) was used to reduce dimensionality and improve interpretability.

### Model Evaluation

We trained five models to evaluate the COMPAS algorithm's predictive accuracy:

1. **Neural Networks**: Leveraged deep learning to capture complex patterns.
2. **Decision Trees**: Used for their interpretability and decision-making transparency.
3. **Linear Regression**: Established a baseline for performance evaluation.
4. **Support Vector Machines (SVM)**: Explored for their performance in high-dimensional spaces.
5. **K-Nearest Neighbors (KNN)**: Applied for its simple and intuitive classification approach.

## Results

The detailed analysis and results, including model performance metrics and visual comparisons, can be found in the `compasAnalysis.ipynb` notebook. Highlights include:

- Model evaluation and comparison.
- Visualizations showcasing the performance of each model.
- Insights into the fairness and implications of using COMPAS in criminal justice decision-making.

## Conclusion

This analysis provides a deep dive into the COMPAS algorithm, contributing to the ongoing discussion about the use of algorithmic tools in criminal justice. We explore both the accuracy and fairness of the system, offering valuable insights for future improvements.
