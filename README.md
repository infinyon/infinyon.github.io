# infinyon.github.io

Helm charts for Fluvio Streaming platform

# Adding Repo

```
helm repo add fluvio https://infinyon.github.io/charts
helm repo update
```

# Installing Fluvio

To install fluvio on AWS EKS

```
helm install fluvio/fluvio --generate-name --set cloud=aws
```

To install fluvio on minikube

```
helm install fluvio/fluvio --generate-name --set cloud=minikube
```
