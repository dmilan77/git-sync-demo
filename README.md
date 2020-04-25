# git-sync-demo
https://github.com/kubernetes/git-sync
```
kubectl apply -f k8-git-sync-demo.yaml

# For alpine-git
kubectl alpine -f alpine-git-init-container-demo.yaml
kubectl port-forward pods/git-repo-demo 8080:80
```
