# BackstageTestRepo

This is a test repo for Backstage.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```
- Docker
  ```sh
    docker pull docker.io/library/node:latest
    ```
- Docker Compose
- ```sh
    docker pull docker.io/library/docker-compose:latest
    ```
- Kubernetes
- ```sh
    kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.0.0/aio/deploy/recommended.yaml
    ```
- Helm
- ```sh
    helm repo add stable https://charts.helm.sh/stable
    ```
- Skaffold
- ```sh
    curl -Lo skaffold https://storage.googleapis.com/skaffold/releases/latest/skaffold-linux-amd64 && chmod +x skaffold && sudo mv skaffold /usr/local/bin
    ```
- Minikube
- ```sh
    minikube start
    ```
- Kustomize
- ```sh
    kubectl kustomize
    ```
- Kubeval
- ```sh
    kubeval
    ```
- Kube-score
- ```sh
    kube-score score
    ```
- Kube-linter
- ```sh
    kube-linter lint
    ```
- Kube-bench
- ```sh
    kube-bench run
    ```
- Kube-hunter
- ```sh
    kube-hunter hunt
    ```