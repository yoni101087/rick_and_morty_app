# Rick and Morty Flask App

This is a simple Flask app that queries the "Rick and Morty" API and returns character data based on specific criteria.

## Helm Chart Deployment

### Prerequisites

- Docker installed
- Kubernetes (Kind or Minikube) installed and running
- Helm installed (https://helm.sh/docs/intro/install/)

### Steps

1/ Install k8s cluster
2/ set the runner
3/ clone the repo
4/ Log in to Docker Hub
5/ Build the Docker Image
6/ Push the Docker Image
7/ Deploy to Kubernetes with helm
8/ test-app


API Endpoints
Health Check: http://<minikube-ip>/healthcheck
Fetch all characters: http://<minikube-ip>/characters

With these steps, you can now deploy the Helm chart to Kubernetes using Kind/Minikube and access the API endpoints to fetch the data.

