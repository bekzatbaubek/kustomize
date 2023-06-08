```sh
minikube start -p hello-kustomize-1
```

```sh
kubectl kustomize overlays/dev-1 --enable-helm | kubectl apply -f - --context hello-kustomize-1
```
