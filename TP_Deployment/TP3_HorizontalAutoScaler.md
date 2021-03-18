# Demo/TP 

https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/


## Metrics API

```
$ kubectl top nodes
```

> Il faut déployer le *metric server*

https://github.com/kubernetes-sigs/metrics-server/releases

> /!\ : Sur un cluster Minikube, il manque une options dans le fichier yaml au niveau du container metrics-server
> --kubelet-insecure-tls


```
$ kubectl apply -f components.yaml
$ kubectl top nodes
```