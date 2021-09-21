kubectl get secrets

kubectl get pod

kubectl get svc

kubectl get pod k8s-mysql -o template --template={{.status.podIP}}

kubectl expose pod k8s-msg-api --port=8080 --name=k8s-srv-msg-api --type=NodePort

minikube ip

kubectl describe service k8s-srv-msg-api