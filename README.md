# mlfowlearn


# Dagshub


```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Himdnk/mlfowlearn.mlflow 
export MLFLOW_TRACKING_USERNAME=Himdnk
export MLFLOW_TRACKING_PASSWORD=49e00d2e16219842d677af95fb2f0638b5a094bb

```

sudo apt update

sudo apt install python3-pip

sudo pip3 install pipenv

sudo pip3 install virtualenv

mkdir mlflow 

cd mlflow

pipenv install mlflow

pipenv install awscli

pipenv install boto3

pipenv shell

aws configure

mlflow server -h 0.0.0.0 --default-artifact-root s3://mlflow-test-23

export MLFLOW_TRACKING_URI=http://ec2-54-147-36-34.compute-1.amazonaws.com:5000/
