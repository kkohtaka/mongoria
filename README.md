# mongoria

**This project is WIP.**

An implementation of MongoDB Replica Set on Kubernetes cluster

## How to Deploy a MongoDB Replica Set

```bash
$ kubectl create -f ./mongo-namespace.yml
$ kubectl create -f ./mongo-service.yml
$ kubectl create -f ./mongo-deployment.yml
$ kubectl create -f ./mongo-init-script-configmap.yml
$ kubectl create -f ./mongo-init-job.yml
```

## How to Deploy a Prometheus service to monitor the MongoDB Replica Set

```bash
$ kubectl create -f ./prometheus-service.yml
$ kubectl create -f ./prometheus-configmap.yml
$ kubectl create -f ./prometheus-deployment.yml
```
