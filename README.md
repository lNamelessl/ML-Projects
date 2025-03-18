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
- Achieved 84% accuracy using decision trees

### Dimensionality Reduction Exercise
An exploration of dimensionality reduction techniques using the MNIST dataset:
- Feature extraction with PCA
- Random Forest classification
- Performance comparison before and after dimensionality reduction
- t-SNE visualization of high-dimensional data
- Maintained high accuracy while reducing feature dimensions

### Ensembles Exercise
Implementation of ensemble learning methods using the MNIST dataset:
- Comparison of different ensemble techniques (Random Forest, Extra Trees, SVM, MLP)
- Voting Classifier implementation
- Stacking Classifier implementation
- Achieved 97.95% accuracy on test data

### Titanic Prediction
Predicting survival on the Titanic using various classification algorithms:
- Data cleaning and preprocessing
- Feature engineering
- Model comparison and evaluation

## Project Structure

ML-Projects/
├── Moon_Classifier.ipynb
├── Moon_Classifier v1.ipynb
├── Dimensionlity_Reduction_Exercise.ipynb
├── Ensembles_Exercise.ipynb
├── Ensembles_Exercise (1).ipynb
├── titanic-prediction.ipynb
├── README.md
├── .gitignore
└── LICENSE

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

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
- Dimensionality reduction (PCA, t-SNE)
- Hyperparameter tuning with GridSearchCV
- Model selection and evaluation
- Ensemble methods (Voting, Stacking)
- Visualization of high-dimensional data

## Results

- Moon Classifier: Achieved 84% accuracy using decision trees
- Dimensionality Reduction: Maintained high accuracy while reducing feature dimensions
- Ensembles Exercise: Achieved 97.95% accuracy using stacking ensemble methods
- Titanic Prediction: Classification of Titanic survival data

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- scikit-learn for providing excellent machine learning tools
- Kaggle and other data sources for the datasets used in these projects