# Titanic Survival Prediction

## Project Description
This project implements two machine learning models, Decision Tree and Random Forest, to predict survival on the Titanic dataset. The models are trained and evaluated using both a synthetic dataset and the Titanic dataset. The goal is to compare the performance of the two models and understand their behavior on real-world data.

## Project Structure

- `main.py`: The main script that loads the data, initializes the models, trains them, and evaluates their performance.
- `decision_tree.py`: Contains the implementation of the Decision Tree model.
- `random_forest.py`: Contains the implementation of the Random Forest model.
- `node.py`: Contains the implementation of the Node class used by the Decision Tree.
- `load_data.py`: Handles data loading and preprocessing, including a function to load the Titanic dataset and generate synthetic data.

## Model Implementation Details

### Decision Tree (`decision_tree.py`)
The Decision Tree class includes methods for training (`train`), predicting (`predict`), and evaluating (`evaluate`). It uses a simple node structure to build the tree and makes use of the Gini impurity for splitting.

### Random Forest (`random_forest.py`)
The Random Forest class initializes multiple Decision Trees and uses bagging to create diverse trees. It aggregates the predictions from individual trees to make the final prediction.

### Node (`node.py`)
The Node class represents each node in the Decision Tree. It includes methods to find the best split based on Gini impurity and recursively build the tree.



