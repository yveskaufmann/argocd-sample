# Setup argocd in minikube

1. `minikube start`
2. `kubectl config use-context minikube` 
3. `kubectl apply -k -f argocd/base`