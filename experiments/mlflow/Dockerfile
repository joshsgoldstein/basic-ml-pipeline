FROM python:3.8-slim-buster

RUN apt-get update && apt-get install -y git

RUN pip install mlflow boto3 pymysql minio sklearn cryptography 

WORKDIR /training
COPY ./tests.py .
COPY ./kc_house_data.csv .
COPY ./train.py .