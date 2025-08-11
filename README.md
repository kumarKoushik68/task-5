 Project Overview
This project is part of the AI & ML Internship program and focuses on applying tree-based models for classification tasks.
We use the Heart Disease Dataset to predict whether a patient is likely to have heart disease based on health-related attributes.

The task covers:

Building and visualizing Decision Trees

Understanding and preventing overfitting

Implementing Random Forests

Comparing model performance

Interpreting feature importance

Evaluating using cross-validation

Dataset
Dataset Name: Heart Disease Dataset (heart.csv)
Target Variable: target

1 → Presence of heart disease

0 → No heart disease

Source: Kaggle – Heart Disease Dataset

 Tools & Libraries
Python 3.x
Pandas, NumPy – Data handling
Matplotlib, Seaborn – Visualization
Scikit-learn – ML models, evaluation, and cross-validation
Graphviz / plot_tree – Decision Tree visualization

Workflow
Load & Explore Data
Checked missing values, data types, and class distribution
Generated correlation heatmap for feature relationships
Preprocessing
Separated features (X) and target (y)
Performed train-test split (80-20 ratio)
Decision Tree
Trained default DecisionTreeClassifier
Visualized the tree using plot_tree
Controlled overfitting with max_depth parameter
Random Forest

Trained RandomForestClassifier with 100 trees

Compared performance with Decision Tree

Visualized feature importances

Evaluation

Accuracy, confusion matrix, classification report

5-fold cross-validation for reliable results
