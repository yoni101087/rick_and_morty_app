# Rick and Morty Flask App

This is a simple Flask app that queries the "Rick and Morty" API and returns character data based on specific criteria.

## Helm Chart Deployment

### Prerequisites

- Docker installed
- Kubernetes (Kind or Minikube) installed and running
- Helm installed (https://helm.sh/docs/intro/install/)

### Steps

1/ Install k8s cluster <br>
2/ set the runner <br>
3/ clone the repo <br> 
4/ Log in to Docker Hub <br>
5/ Build the Docker Image <br>
6/ Push the Docker Image <br>
7/ Deploy to Kubernetes with helm <br>
8/ test-app


API Endpoints
Health Check: http://<minikube-ip>/healthcheck
Fetch all characters: http://<minikube-ip>/characters

With these steps, you can now deploy the Helm chart to Kubernetes using Kind/Minikube and access the API endpoints to fetch the data.

