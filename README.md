# Basic Machine Learning Lifecycle Pipeline

## Purpose
Build a basic mL pipeline using open source technology today

Tech used in this pipeline:
- Python
- Docker/Kubernetes
- Mlflow
- Minio
- Seldon Core
- Github
- Jenkins
- ArgoCD


## Setup the experiments
1. Go into experiments
2. Run `docker-compose up -d` to start up the underlying services

Training the Experiment with mlFlow

1. Run `docker exec -it mlflow_server python train.py` to kick off the training and experiments


Build API Endpoint for model prediction



Test with microservice:
`seldon-core-microservice MyModel REST --service-type MODEL`


# Credits

[Build Docker File with Python Wrapper Class](https://docs.seldon.io/projects/seldon-core/en/latest/python/python_wrapping_docker.html)

[A Simple MLOps Pipeline on Your Local Machine](https://towardsdatascience.com/a-simple-mlops-pipeline-on-your-local-machine-db9326addf31)