```
kubectl apply -k argocd-bootstrap
kubectl patch svc argocd-server -n argocd -p '{"spec": {"type": "LoadBalancer"}}'
```
