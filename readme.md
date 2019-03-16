## POD

```kubectl run nginx --image=nginx --restart=Never --dry-run -o yaml```

list

```kubectl get pods```

```kubectl delete pod <pod-name>```

```kubectl edit pod <pod-name>```

```kubectl apply -f <file-name>```

```kubectl explain Pod.spec```

```kubectl port-forward <pod-namee> <host-port>:<container-port>```

## Namespace

```kubectl get namespace```

## Deployments

```kubectl run nginx --image=nginx --restart=Always --replicas=3  --dry-run -o yaml > k8s/deployment.yaml```