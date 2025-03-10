# I add information about the computer languages that the information was missing.

# Machine Learning From Scratch

## About
Python implementations of some of the fundamental Machine Learning models and algorithms from scratch.

The purpose of this project is not to produce as optimized and computationally efficient algorithms as possible 
but rather to present the inner workings of them in a transparent way.
The reason the project uses scikit-learn is to evaluate the implementations on sklearn.datasets.

Feel free to [reach out](mailto:eriklindernoren@gmail.com) if you can think of ways to expand this project.

## Table of Contents
- [Machine Learning From Scratch](#machine-learning-from-scratch)
  * [About](#about)
  * [Table of Contents](#table-of-contents)
  * [Usage](#usage)
    + [Installation](#installation)
    + [Regression](#regression)
    + [Classification](#classification)
    + [Clustering](#clustering)
    + [Association Analysis](#association-analysis)
  * [Current Implementations](#current-implementations)
    + [Supervised Learning](#supervised-learning)
    + [Unsupervised Learning](#unsupervised-learning)
    
## Usage
### Installation
    $ python setup.py install


### Regression
    $ python mlfromscratch/supervised_learning/regression.py

<p align="center">
    <img src="http://eriklindernoren.se/images/prr.png" width="640"\>
</p>
<p align="center">
    Figure: Polynomial ridge regression of temperature data measured in <br> 
    Linköping, Sweden 2016.
</p>

### Classification
    $ python mlfromscratch/supervised_learning/multilayer_perceptron.py

<p align="center">
    <img src="http://eriklindernoren.se/images/mlp4.png" width="640">
</p>
<p align="center">
    Figure: Classification of the digit dataset using an MLP with two <br>
    hidden layers.
</p>

### Clustering
    $ python mlfromscratch/unsupervised_learning/dbscan.py
   
<p align="center">
    <img src="http://eriklindernoren.se/images/dbscan3.png" width="640">
</p>
<p align="center">
    Figure: Clustering of the moons dataset using DBSCAN.
</p>

### Association Analysis
    $ python mlfromscratch/unsupervised_learning/apriori.py 
    +-------------+
    |   Apriori   |
    +-------------+
    Minimum Support: 0.25
    Minimum Confidence: 0.8
    Transactions:
        [1, 2, 3, 4]
        [1, 2, 4]
        [1, 2]
        [2, 3, 4]
        [2, 3]
        [3, 4]
        [2, 4]
    Frequent Itemsets:
        [1, 2, 3, 4, [1, 2], [1, 4], [2, 3], [2, 4], [3, 4], [1, 2, 4], [2, 3, 4]]
    Rules:
        1 -> 2 (support: 0.43, confidence: 1.0)
        4 -> 2 (support: 0.57, confidence: 0.8)
        [1, 4] -> 2 (support: 0.29, confidence: 1.0)


## Current Implementations
### Supervised Learning
- [Adaboost](mlfromscratch/supervised_learning/adaboost.py)
- [Bayesian Regression](mlfromscratch/supervised_learning/bayesian_regression.py)
- [Decision Tree](mlfromscratch/supervised_learning/decision_tree.py)
- [Gradient Boosting](mlfromscratch/supervised_learning/gradient_boosting.py)
- [K Nearest Neighbors](mlfromscratch/supervised_learning/k_nearest_neighbors.py)
- [Linear Discriminant Analysis](mlfromscratch/supervised_learning/linear_discriminant_analysis.py)
- [Linear Regression](mlfromscratch/supervised_learning/regression.py)
- [Logistic Regression](mlfromscratch/supervised_learning/logistic_regression.py)
- [Multi-class Linear Discriminant Analysis](mlfromscratch/supervised_learning/multi_class_lda.py)
- [Multilayer Perceptron](mlfromscratch/supervised_learning/multilayer_perceptron.py)
- [Naive Bayes](mlfromscratch/supervised_learning/naive_bayes.py)
- [Perceptron](mlfromscratch/supervised_learning/perceptron.py)
- [Polynomial Regression](mlfromscratch/supervised_learning/regression.py)
- [Random Forest](mlfromscratch/supervised_learning/random_forest.py)
- [Ridge Regression](mlfromscratch/supervised_learning/regression.py)
- [Support Vector Machine](mlfromscratch/supervised_learning/support_vector_machine.py)
- [XGBoost](mlfromscratch/supervised_learning/xgboost.py)

### Unsupervised Learning
- [Apriori](mlfromscratch/unsupervised_learning/apriori.py)
- [DBSCAN](mlfromscratch/unsupervised_learning/dbscan.py)
- [FP-Growth](mlfromscratch/unsupervised_learning/fp_growth.py)
- [Gaussian Mixture Model](mlfromscratch/unsupervised_learning/gaussian_mixture_model.py)
- [K-Means](mlfromscratch/unsupervised_learning/k_means.py)
- [Partitioning Around Medoids](mlfromscratch/unsupervised_learning/partitioning_around_medoids.py)
- [Principal Component Analysis](mlfromscratch/unsupervised_learning/principal_component_analysis.py)
