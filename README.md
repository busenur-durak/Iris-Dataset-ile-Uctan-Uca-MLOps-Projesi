# Iris MLOps Pipeline

A full pass from the Iris dataset to a served model: preprocess, train, track, version, and expose a prediction API.

Logistic Regression, Random Forest, and SVM are compared. MLflow records parameters, metrics, and artifacts. DVC versions the processed data. The chosen model is served with FastAPI at `/predict`, and a Dockerfile packages that API.

The Iris dataset is the teaching example. The point of the repo is the pipeline around it.

## Stack

Python, scikit-learn, MLflow, DVC, FastAPI, Docker

## Author

Busenur Durak · Management Information Systems, İzmir Bakırçay University
