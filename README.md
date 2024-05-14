# Minikube
Minikube repository

## Commands

- Using VirtualBox

```sh
minikube start --kubernetes-version='v1.23.0' --driver='virtualbox' --memory=8196 -p gitops
```
- Using Docker

```sh
minikube start --driver='docker'
```

## References

- https://minikube.sigs.k8s.io/docs/
