# Docker container for running the spam detection experiment

This repository holds code for creating a docker container which then is used to run the MLflow project of spam detection problem.

MLflow project repo - https://github.com/rohithteja/mlflow-twitter-social-spam

## Command line arguments
`git clone https://github.com/rohithteja/docker-img-socialspam.git`
`cd docker-img-socialspam`
`docker build -t docker-img-socialspam:1.0 .`

After building the docker container, run the MLflow project using the code present in the project repo.
