# Software to Install

## Docker Daemon
This tool is used to create and interact with Docker Images locally.
https://docs.docker.com/get-docker/

## Google Cloud CLI (and kubectl)
This tool allows you to interact with Google Cloud, and also includes `kubectl` which is a Kubernetes utility we will be using to send instructions to Kuberentes.
https://cloud.google.com/sdk/docs/install

# Important Commands
## Docker Daemon Commands
Commands to your local Docker Daemon to build and manage Docker Images locally

### Build / Compile a Docker Image
```
$ docker build --tag app:1.0 .
```

### Run a Docker Image Locally
```
$ docker run app:1.0
```

### Send a Docker Image to the Docker Registry
```
$ docker push app:1.0
```

### Download a Docker Image from the Docker Registry
```
$ docker pull app:1.0
```

---

## Kubernetes Apply Commands
Commands to your Kubernetes Cluster to update itself to your specification

### Apply changes within file to Cluster
```
kubectl apply -f <FILE_PATH>
```
