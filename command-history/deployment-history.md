10410* docker build -t node-demo .
10411* docker run --rm node-demo  /bin/sh -c "echo 'hello-world'"
10412* docker run --rm node-demo  /bin/sh -c "echo env"
10413* docker run --rm node-demo  /bin/sh -c "env"
10414* docker run --rm node-demo
10415  kubectl get pods -o wide
10416  kubectl explain Pod.spec
10417* kubectl run nginx --image=nginx --restart=Always --replicas=3  --dry-run -o yaml > k8s/deployment.yaml
10418  kubectl get pods
10419  kubectl delete pod nginx-pod  nginx-staging
10420  kubectl get pods,deploy
10421* kubectl run nginx --image=nginx --restart=Never
10422  kubectl get pods,deploy
10423  clear
10424  kubectl get pods,deploy
10425* kubectl run nginx --image=nginx --restart=Always
10426  kubectl get pods,deploy
10427  kubectl delete pod/nginx
10428  kubectl get pods,deploy
10429  kubectl delete pod/nginx-64f497f8fd-pfvqm
10430  kubectl get pods,deploy
10431  kubectl edit deployment nginx
10432  kubectl get pods,deploy
10433  clear
10434  kubectl get pods,deploy
10435  kubectl edit deployment nginx
10436  kubectl get pods,deploy
10437  kubectl edit deployment nginx
10438  kubectl get pods,deploy
10439  kubectl describe pod/nginx-64f497f8fd-t78bz 
10440  clear
10441  kubectl edit deployment nginx
10442  kubectl get pods,deploy
10443  kubectl run nginx-sample --image=nginx --restart=Never
10444  kubectl get pods,deploy
10445  kubectl get pods --show-labels
10446  kubectl get pods -l run=nginx
10447  kubectl get pods -l app=nginx
10448  kubectl delete pod nginx-64f497f8fd-tcxj7 nginx-64f497f8fd-t78bz
10449  kubectl get pods,deploy
10450  kubectl delete deploy/nginx
10451  kubectl get pods --all-namespaces
10452  kubectl get pods
10453  cleear
10454  clear
10455  kubectl top pods]
10456  kubectl top pods
10457  kubectl top nodes
10458  kubectl delete pod nginx -n apps
10459  kubectl get pods -n apps
10460  kubectl delete pod nginx-app  -n apps
10461  kubectl get pods
10462  kubectl delete  pods nginx-sample
10463  clear
10464* kubectl apply -f k8s/deployment.yaml
10465  kubectl get pods,deploy
10466  kubectl get pods -l app=nginx
10467  kubectl get pods -o wide
10468  kubectl get pods --show-labels
10469  kubectl describe pod nginx-5b7c6bcbbd-7tstn 
10470  clear