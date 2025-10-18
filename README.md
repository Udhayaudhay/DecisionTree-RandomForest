# Decision Tree Breast Cancer Classifier

## Project Overview
This project implements a **Decision Tree classifier** to predict **breast cancer** (malignant vs. benign) using the `sklearn` breast cancer dataset.  
It demonstrates data splitting, model training, hyperparameter tuning, and visualization of the tree structure with **Graphviz**.  

## Features
- Load the breast cancer dataset from `sklearn.datasets`.
- Split dataset into training and testing subsets.
- Train a Decision Tree model with customizable hyperparameters:
  - `max_depth` – Maximum depth of the tree.
  - `min_samples_leaf` – Minimum number of samples per leaf node.
  - `min_samples_split` – Minimum number of samples required to split an internal node.
- Visualize the trained tree using **Graphviz**.
- Evaluate model performance using accuracy metrics.

## Getting Started

### Prerequisites
- Python 3.x
- Packages: `scikit-learn`, `graphviz`

Install dependencies using:

```bash

# Random Forest Machine Learning Project

## Project Overview
This project demonstrates the use of **Random Forest algorithms** for both classification and regression tasks.  
It includes feature importance analysis, hyperparameter tuning, and model evaluation with out-of-bag (OOB) error estimation.

---

## Features
- **Random Forest Classifier**
  - Trained on the Iris dataset to classify flower species.
  - Supports `n_estimators`, `random_state`, `criterion` (gini/entropy), and `n_jobs` hyperparameters.
  - Feature importance analysis and visualization using Matplotlib.

- **Random Forest Regressor**
  - Trained on datasets (e.g., Boston Housing replaced with California Housing due to scikit-learn update).
  - Supports regression tasks with `n_estimators`, `random_state`, and `n_jobs`.
  - Feature selection using `SelectFromModel`.

- **Model Evaluation**
  - Cross-validation for performance estimation.
  - Out-of-bag (OOB) score for classifier evaluation.

---

## Usage

### Install dependencies
```bash
pip install scikit-learn matplotlib pandas numpy

pip install scikit-learn graphviz
