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
pip install scikit-learn graphviz
