# Random Forest Classifier Tutorial: Credit Card Fraud Detection

This repository contains a Jupyter notebook that demonstrates how to implement a **Random Forest Classifier** to detect credit card fraud. The tutorial is based on an article by Davis David, originally published on freeCodeCamp.


## Overview
The project explores the use of tree-based algorithms for machine learning, specifically focusing on the Random Forest algorithm. It includes:
* An explanation of how Random Forest works (sampling, tree creation, and voting).
* Data preprocessing techniques such as scaling.
* Evaluation strategies for imbalanced datasets.

## Dataset
The notebook uses the **Credit Card Fraud Detection** dataset from Kaggle.
* **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
* **Description:** The dataset contains transactions made by credit cards in September 2013 by European cardholders. It is highly imbalanced, with the "fraud" class accounting for only a tiny fraction of all transactions.

## Evaluation Method
Because of the high class imbalance, standard accuracy (confusion matrix accuracy) is not a meaningful metric. Instead, this tutorial recommends using:
* **Area Under the Precision-Recall Curve (AUPRC)**.

## Requirements
The following Python libraries are required to run the notebook:
* `scikit-learn`
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `kagglehub` (for downloading the dataset)

You can install the primary machine learning library using:
```bash
pip install scikit-learn
```

## How to Run
1.  **Download the Dataset:** The notebook uses `kagglehub` to download the dataset directly from Kaggle.
2.  **Execute Cells:** Run the cells sequentially to load the data, perform exploratory data analysis (`df.describe()`), and train the Random Forest model.

## Acknowledgments
* **Author:** Davis David.
* **Original Article:** [How to Use Tree-Based Algorithms for Machine Learning](https://www.freecodecamp.org/news/how-to-use-the-tree-based-algorithm-for-machine-learning/).
* **Article's publication date:** August 06, 2020
* **This notebook creation date:** January 28, 2026.
