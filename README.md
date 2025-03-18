# ML-Projects

A collection of machine learning projects exploring various algorithms, techniques, and datasets.

## Overview

This repository contains a variety of machine learning projects implemented in Jupyter notebooks. Each project focuses on different aspects of machine learning, from classification and dimensionality reduction to ensemble methods and feature selection.

## Projects

### Moon Classifier
A binary classification project using the scikit-learn `make_moons` dataset. This project demonstrates:
- Data preprocessing with PCA
- Hyperparameter tuning with GridSearchCV
- Decision tree classification
- Model evaluation

### Dimensionality Reduction Exercise
An exploration of dimensionality reduction techniques using the MNIST dataset:
- Feature extraction with PCA
- Random Forest classification
- Performance comparison before and after dimensionality reduction

### Telecom Customer Churn
A practical application of machine learning to predict customer churn in a telecom dataset:
- Feature engineering and selection using RFE
- Model comparison (Random Forest, SVM, Logistic Regression, XGBoost, LightGBM)
- Model evaluation with classification metrics
- Model persistence for deployment

### Ensembles Exercise
Implementation of ensemble learning methods using the MNIST dataset:
- Comparison of different ensemble techniques
- Evaluation of model performance

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, xgboost, lightgbm

### Usage
1. Clone the repository:
```bash
git clone https://github.com/lNamelessl/ML-Projects.git
cd ML-Projects
```

2. Open the notebooks in Jupyter or Google Colab to explore the projects.

3. Each notebook is self-contained with detailed explanations and code comments.

## Key Techniques Demonstrated

- Data preprocessing and feature engineering
- Dimensionality reduction
- Hyperparameter tuning
- Model selection and evaluation
- Ensemble methods
- Feature selection

## Results

- Moon Classifier: Achieved 84% accuracy using decision trees
- Dimensionality Reduction: Maintained high accuracy (97%) while reducing feature dimensions
- Telecom Customer Churn: Achieved ~80% accuracy in predicting customer churn

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- scikit-learn for providing excellent machine learning tools
- Kaggle and other data sources for the datasets used in these projects