# Operationalize-a-Machine-Learning-Microservice-API_UdacityProject
Operationalize a Machine Learning Microservice API Udacity Project

## Project Overview
Deploy a containerized Python flask application to serve out predictions (inference) about housing prices through API calls. It uses a a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features. 

## Project Procedure

  1. Create a virtualenv and activate it.
  2. Docker installation.
  3. Lints checks with hadolint and pylint.
  4. Installation of Kubernetes and Minikube .
  5. Test project code using linting.
  6. Complete a Dockerfile to containerize this application
  7. Deploy containerized application using Docker and make a prediction
  8. Upload a complete Github repo with CircleCI to indicate the code has been tested
  9. Deploy a container using Kubernetes and make a prediction
  
## Dockerfile

 1. Dockerfile configuration 
 2. Run a Container (./run_docker.sh)& Make a Prediction(./make_prediction.sh)
 3. Logging in the docker_out.txt file
 4. Upload docker image to docker hub (upload_docker.sh)

## Kubernetes

 1. Configure Kubernetes to Run Locally (install Minikube)
 2. Deploy with Kubernetes (./run_kubernetes.sh)
 3. Savings Output logs in the file kubernetes.out.txt

## CircleCI Integration

This repository has been verified with CircleCI
  
  


[![CircleCI](https://circleci.com/gh/mohmagdy1016/Operationalize-a-Machine-Learning-Microservice-API_UdacityProject.svg?style=svg)](https://circleci.com/gh/mohmagdy1016/Operationalize-a-Machine-Learning-Microservice-API_UdacityProject)
