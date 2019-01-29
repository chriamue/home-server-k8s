# home-server-k8s
home server on kubernetes

## quickstart

```bash
kubectl create namespace home-server
kubectl create -f . -f environment
kubectl get services
kubectl delete -f . -f environment
```

```bash
kubectl get all --all-namespaces
```

## services

### openldap
[https://github.com/osixia/docker-openldap/tree/stable/example/kubernetes/using-secrets]()

### nextcloud

[https://hub.docker.com/r/wonderfall/nextcloud/]()
[https://github.com/sameersbn/docker-nextcloud/tree/master/kubernetes]()

### gitlab

[https://github.com/IBM/Kubernetes-container-service-GitLab-sample]()