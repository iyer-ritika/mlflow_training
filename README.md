# mlflow_training

# Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains the resources for my tutorial **"Managing the end-to-end machine learning lifecycle with MLFlow"** at pyData/pyCon Berlin 2019.

# Basic setup

## Setup the environment
- clone this repository
- **with virtualenv (recommended)**
  - install virtualenv: `pip install virtualenv`
  - create a new environment: `virtualenv mlflow_tutorial`
  - activate the environment: `source /mlflow_tutorial/bin/activate`
  - run `pip install -r requirements.txt`
 
 
## The notebook
- run `jupyter notebook`
- open hands_on_example.ipynb

## To launch MLflow Server
- run the command: mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host localhost --port 5000
- Go to your browser and open localhost:5000 to see the mlflow ui
