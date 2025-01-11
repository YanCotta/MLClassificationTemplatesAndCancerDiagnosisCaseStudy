# Machine Learning Classification Templates

This repository provides ready-to-use templates for common machine learning classification algorithms implemented in Python using scikit-learn + a medical dataset that provides a real-world application of classification algorithms in cancer diagnosis.

## Overview

These templates are designed to help you quickly implement and compare different classification algorithms. Each template includes detailed comments explaining the algorithm, its use cases, advantages, limitations, and key parameters.

## Included Templates

### 1. Logistic Regression (`logistic_regression.py`)
- Basic binary classification algorithm
- Best for: Linear relationships, binary outcomes
- Advantages: Simple, interpretable, computationally efficient
- Limitations: Cannot handle non-linear relationships well

### 2. K-Nearest Neighbors (`k_nearest_neighbors.py`) 
- Instance-based learning method
- Best for: Small to medium datasets with clear patterns
- Advantages: No training phase, handles non-linear data
- Limitations: Computationally expensive for large datasets

### 3. Support Vector Machine (`support_vector_machine.py`)
- Linear classification with maximum margin
- Best for: High-dimensional data, clear margins between classes
- Advantages: Effective in high dimensions, memory efficient
- Limitations: Not suitable for large datasets

### 4. Kernel SVM (`kernel_svm.py`)
- Non-linear classification using kernel trick
- Best for: Complex non-linear relationships
- Advantages: Can handle non-linear data effectively
- Limitations: Computationally intensive

### 5. Naive Bayes (`naive_bayes.py`)
- Probabilistic classifier based on Bayes' theorem
- Best for: Text classification, spam filtering
- Advantages: Fast, efficient with high-dimensional data
- Limitations: Assumes feature independence

### 6. Decision Tree (`decision_tree_classification.py`)
- Tree-structured classifier
- Best for: Cases requiring interpretable results
- Advantages: Easy to understand, visualize
- Limitations: Can overfit, unstable

### 7. Random Forest (`random_forest_classification.py`)
- Ensemble of decision trees
- Best for: Complex classification tasks
- Advantages: High accuracy, handles overfitting
- Limitations: Less interpretable, computationally intensive

## Example Dataset: Breast Cancer Classification

Included is a breast cancer diagnostic dataset (`Data.csv`) from the UCI Machine Learning Repository.

### Dataset Information
- **Features**: 10 real-valued features computed from digitized breast mass images
- **Target**: Binary classification (2 = benign, 4 = malignant)
- **Samples**: 699 instances

### Features Description
1. Clump Thickness
2. Uniformity of Cell Size
3. Uniformity of Cell Shape
4. Marginal Adhesion
5. Single Epithelial Cell Size
6. Bare Nuclei
7. Bland Chromatin
8. Normal Nucleoli
9. Mitoses
10. Class (2 for benign, 4 for malignant)

This medical dataset provides a real-world application of classification algorithms in cancer diagnosis.

## Usage

1. Clone this repository
2. Install required packages: `pip install numpy pandas scikit-learn matplotlib`
3. Choose a template based on your needs
4. Replace 'ENTER_THE_NAME_OF_YOUR_DATASET_HERE.csv' with your dataset path
5. Run the script

## Best Practices

- Always scale your features
- Split data into training and test sets
- Try multiple algorithms on your problem
- Use cross-validation for more reliable results
- Consider computational resources when choosing algorithms

## Requirements

- Python 3.x
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for improvements.

## License

MIT License
Copyright (c) 2025 Yan Cotta
