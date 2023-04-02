# ArgoCD-CICD-app-repo

This repository demonstrates how to set up a CI/CD pipeline for a Python application using ArgoCD on Google Kubernetes Engine (GKE). The pipeline will automatically build and deploy the application to the Kubernetes cluster on GKE.


# Architecture :

![Untitled Diagram drawio](https://user-images.githubusercontent.com/105196334/229345148-d2ac5543-9853-49e2-a763-fe149273aa95.png)


Deployment repo : [ArgoCD-CICD-deployment-repo](https://github.com/shivam779823/ArgoCD-CICD-deployment-repo)


# Prerequisites
Before you begin, you'll need to have the following:

1. A GKE cluster set up with the kubectl command-line tool configured to connect to the cluster.
2. A GitHub account.
3. A DockerHub account (or another container registry of your choice).
4. ArgoCD installed on the Kubernetes cluster.

# Setup

1. Create two repos for app code and depoyment/helm charts code.
2. Add github tokens to workflows.
3. Create GKE Clusetr Install argoCD. 
4. Setup argocd integration with deployment repo using ssh method
5. Setup webhook for slack (optional).

# ArgoCD UI

<img width="1080" alt="image" src="https://user-images.githubusercontent.com/105196334/229345203-4d9b3620-486a-4a0e-a903-906ce20fb65b.png">


# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

connect with me :

[LINKEDIN ](https://www.linkedin.com/in/shivam1mahajan).






