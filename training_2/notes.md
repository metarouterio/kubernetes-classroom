# Docker Daemon Commands
Commands to your local Docker Daemon to build and manage Docker Images locally

## Build / Compile a Docker Image
```
$ docker build --tag app:1.0 .
```

## Run a Docker Image Locally
```
$ docker run app:1.0
```

## Send a Docker Image to the Docker Registry
```
$ docker push app:1.0
```

## Download a Docker Image from the Docker Registry
```
$ docker pull app:1.0
```
---

# Kubernetes Apply Commands
Commands to your Kubernetes Cluster to update itself to your specification

## Apply changes within file to Cluster
```
kubectl apply -f <FILE_PATH>
```
