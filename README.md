#  Kidney-Disease-Classification-Deep-Learning-Project

## Workflows

1.Update config.yaml
2.Update secrets.yaml [Optional]
3.Update params.yaml
4.Update the entity
5.Update the configuration manager in src config
6.Update the components
7.Update the pipeline
8.Update the main.py
9.Update the dvc.yaml
10.app.py


# How to run?
...
# STEPS:

# Clone the repository

'''bash
https://github.com/kjayshree017/Kidney-Disease-Classification-Deep-Learning-Project
''''
...
# STEP 01- Create a conda environment after opening the repository
'''bash
conda create -n cnncls python=3.8 -y
conda activate cnncls
'''
...
# STEP 02- install the requirements
'''bash
pip install -r requirements.txt
'''

# Finally run the following command
python app.py

# Now,

### open up you local host and port

## MLflow

### Documentation
https://mlflow.org/docs/latest/index.html


### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kjayshree017/Kidney-Disease-Classification-Deep-Learning-Project.mlflow
MLFLOW_TRACKING_USERNAME=kjayshree017
MLFLOW_TRACKING_PASSWORD=f772e34ecc9a3a4b18fe0f6af0dfc89dc72b8400
python script.py




### Run this to export as env variables:
'''bash
export MLFLOW_TRACKING_URI=https://dagshub.com/kjayshree017/Kidney-Disease-Classification-Deep-Learning-Project.mlflow 

export MLFLOW_TRACKING_USERNAME==kjayshree017

export MLFLOW_TRACKING_PASSWORD=f772e34ecc9a3a4b18fe0f6af0dfc89dc72b8400

'''

#### DVC cmd
1. dvc init
2. dvc repro
3. dvc dag