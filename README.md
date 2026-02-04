# K-Nearest Neighbors (KNN) Implementation with Cross-Validation & Pipeline

This project demonstrates the implementation of the K-Nearest Neighbors
(KNN) classification algorithm using Python and scikit-learn with
hyperparameter tuning and pipelines.

## Project Overview
KNN is a distance-based supervised learning algorithm used for
classification tasks. This project improves model performance by:

- Feature scaling
- Pipeline integration
- Hyperparameter tuning using GridSearchCV
- Cross-validation

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

## Key Concepts Applied

### Pipeline
Used to combine preprocessing (StandardScaler) and model training into a
single workflow.

### Cross-Validation
5-fold cross-validation ensures robust and reliable model evaluation.

### Hyperparameter Tuning
GridSearchCV is used to find optimal:
- Number of neighbors (k)
- Weight function

## Workflow
1. Data loading
2. Train-test split
3. Feature scaling
4. Pipeline creation
5. Hyperparameter tuning with GridSearchCV
6. Model training
7. Evaluation

## Evaluation Metrics
- Accuracy Score
- Best Parameters

## How to Run

1. Clone the repository
```bash
git clone https://github.com/Anshika135/knn-classifier-implementation.git
