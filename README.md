# basic-ml-pipeline


1. Go into experiments
2. Run `docker-compose up -d` to start up the underlying services

Training the Experiment with mlFlow

1. use `docker exec -it mlflow_server bash` to enter the terminal within the container running mLFlow 
2. run `python train.py`

Build API Endpoint for model prediction

Follow based on this documentation:
[Build Docker File with Python Wrapper Class](https://docs.seldon.io/projects/seldon-core/en/latest/python/python_wrapping_docker.html)
