# COMP 551 Applied Machine Learning Course Project: Self-implemented KNN & DT Algorithms on Health Data

## Overview

This repository contains the implementation of two essential machine learning algorithms: K-Nearest Neighbors (KNN) and Decision Trees (DT), applied to healthcare-related datasets. Our analysis focuses on the National Health and Nutrition Examination Survey (NHANES) 2013-2014 Age Prediction Subset and the Breast Cancer Wisconsin dataset. Through detailed exploration, we investigate the strengths and weaknesses of each algorithm in different scenarios, evaluating their performance based on accuracy and AUROC (Area under the Receiver Operating Characteristic Curve).

## Datasets

- **NHANES 2013-2014 Age Prediction Subset**: Administered by the CDC, this dataset provides comprehensive health and nutrition information of a nationally representative sample of the US population. Our analysis utilizes a subset of features related to respondents' health and physical activity.

- **Breast Cancer Wisconsin Dataset**: A 9-feature dataset collected over a period of 2 years, providing data on breast cancer cases. The dataset includes information on tumor characteristics and was used to evaluate the performance of the implemented algorithms.

## Algorithms

- **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification and regression. The KNN implementation in this repository explores various distance metrics and 'k' values to optimize performance.

- **Decision Trees (DT)**: A tree-like model of decisions where each node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label. The DT implementation focuses on selecting the best attribute splits based on different cost functions to build an optimal tree.

## Results

Our findings indicate that both KNN and DT algorithms perform significantly well on the CANCER dataset, with KNN slightly outperforming DT on both datasets. The detailed analysis and comparison of the algorithms' performance are documented in the included Jupyter notebook (`KNN_DT.ipynb`) and the assignment report (`KNN_DT.pdf`).

## Contributors

- Jimmy Sheng
- Iris Wang
- Keyu Wang

## Citations

Refer to the `Citations` section in the `KNN_DT.pdf` for detailed references and sources utilized in this project.

---

Feel free to adjust the content as needed based on additional details or specific requirements for your repository.
