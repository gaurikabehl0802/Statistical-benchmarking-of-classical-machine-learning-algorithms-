# Statistical Benchmarking and Robustness Analysis of Machine Learning Classifiers

## Overview

This project presents a comparative study of multiple machine learning algorithms across different benchmark datasets. It also evaluates model robustness under label noise conditions to simulate real-world data imperfections.

## Algorithms Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* K-Nearest Neighbors (KNN)
* Multi-Layer Perceptron (MLP)
* XGBoost(for robustness analysis)

## Datasets

* Breast Cancer Dataset (Binary Classification)
* Wine Dataset (Multi-class Classification)
* Digits Dataset (Image Classification)

## Methodology

* Stratified 5-fold cross-validation
* Accuracy used as evaluation metric
* Statistical significance testing using Wilcoxon signed-rank test

## Key Results

* Logistic Regression performed best on Breast Cancer dataset (95.43%)
* Random Forest performed best on Wine dataset (98.30%)
* SVM performed best on Digits dataset (98.77%)

## Robustness Analysis

* Introduced 20% label noise
* Evaluated how model performance degrades under noisy data
* Observed that ensemble models showed better robustness

## Key Insight

This project demonstrates the principle of the No Free Lunch Theorem — no single algorithm performs best across all datasets.

## Tools & Technologies

* Python
* Scikit-learn
* XGBoost
* Pandas
* Matplotlib

## Project Files

* `ml_benchmark_study.ipynb` → Main implementation
* `research_paper.pdf` → Detailed report

## Author

[Gaurika Behl]
