# End-to-End-Cancer-Classification-Using-MLFlow

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

## MLFlow
## Dagshub 
[dagshub](https://dagshub.com)

"MLFLOW_TRACKING_URI" = "https://dagshub.com/ngynhoainamtse/End-to-End-Cancer-Classification-Using-MLFlow.mlflow"
"MLFLOW_TRACKING_USERNAME" = "ngynhoainamtse"
"MLFLOW_TRACKING_PASSWORD" = "de623beb80217b2d0883c2d4026e100e82ef39bd"

python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/ngynhoainamtse/End-to-End-Cancer-Classification-Using-MLFlow.mlflow

export MLFLOW_TRACKING_USERNAME=ngynhoainamtse 

export MLFLOW_TRACKING_PASSWORD=de623beb80217b2d0883c2d4026e100e82ef39bd

```

## DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

# About MLflow & DVC

## MLflow

* Its Production Grade
* Trace all of your expriements
* Logging & taging your model

## DVC

* Its very lite weight for POC only
* lite weight expriements tracker
* It can perform Orchestration (Creating Pipelines)
