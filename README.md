Based on the details provided in the assignment report, here is a template for a README file for the GitHub repository named "comp551_a1" which focuses on KNN & DT implementations on Health data:

---

# comp551_a1: KNN & DT Implementations on Health Data

## Overview

This repository contains the implementation of two essential machine learning algorithms: K-Nearest Neighbors (KNN) and Decision Trees (DT), applied to healthcare-related datasets. Our analysis focuses on the National Health and Nutrition Examination Survey (NHANES) 2013-2014 Age Prediction Subset and the Breast Cancer Wisconsin dataset. Through detailed exploration, we investigate the strengths and weaknesses of each algorithm in different scenarios, evaluating their performance based on accuracy and AUROC (Area under the Receiver Operating Characteristic Curve).

## Datasets

- **NHANES 2013-2014 Age Prediction Subset**: Administered by the CDC, this dataset provides comprehensive health and nutrition information of a nationally representative sample of the US population. Our analysis utilizes a subset of features related to respondents' health and physical activity.

- **Breast Cancer Wisconsin Dataset**: A 9-feature dataset collected over a period of 2 years, providing data on breast cancer cases. The dataset includes information on tumor characteristics and was used to evaluate the performance of the implemented algorithms.

## Algorithms

- **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification and regression. The KNN implementation in this repository explores various distance metrics and 'k' values to optimize performance.

- **Decision Trees (DT)**: A tree-like model of decisions where each node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label. The DT implementation focuses on selecting the best attribute splits based on different cost functions to build an optimal tree.

## Requirements

- Python 3.x
- Libraries: NumPy, pandas, scikit-learn, matplotlib

## Installation

Clone this repository to your local machine:

```
git clone https://github.com/yourusername/comp551_a1.git
```

Navigate to the cloned repository:

```
cd comp551_a1
```

## Usage

To run the KNN implementation on the NHANES dataset:

```
python knn_nhanes.py
```

To run the DT implementation on the Breast Cancer Wisconsin dataset:

```
python dt_cancer.py
```

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
