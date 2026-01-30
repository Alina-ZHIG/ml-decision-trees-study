# ML Decision Trees Study

This project is a pet research project focused on studying and comparing
tree-based machine learning algorithms for classification tasks.

The project explores the behavior of Decision Tree, Random Forest, and
Extra Trees classifiers on synthetic datasets, including binary and
multi-class classification, handling imbalanced data, and hyperparameter tuning.

## Objectives
- Study decision boundaries of tree-based models
- Compare single trees and ensemble methods
- Analyze model performance on balanced and imbalanced datasets
- Explore the impact of hyperparameters on classification quality

## Implemented Models
- Decision Tree Classifier
- Random Forest Classifier
- Extra Trees Classifier

## Key Features
- Data loading and preprocessing
- Train/test split
- Visualization of data points and decision boundaries
- Model evaluation using MSE and classification metrics
- Handling imbalanced datasets using class weights
- Hyperparameter tuning with GridSearchCV
- Cross-validation for model comparison

## Technologies Used
- Python
- NumPy
- Matplotlib
- scikit-learn

## Evaluation Metrics
- Mean Squared Error (MSE)
- Precision
- Recall
- F1-score
- Cross-validation accuracy

## Project Structure
- `Lab2.ipynb` — Jupyter Notebook with full implementation
- `README.md` — project description

## Results
The experiments demonstrate that ensemble methods (Random Forest and Extra Trees)
provide more stable and accurate decision boundaries compared to a single
Decision Tree. Handling class imbalance using balanced class weights improves
classification performance on minority classes.

## How to Run
1. Open the notebook file (`Lab2.ipynb`)
2. Run all cells sequentially
3. Consider adjusting model hyperparameters to explore their impact


This project was created for educational purposes and as part of a personal
portfolio to demonstrate practical machine learning skills.
