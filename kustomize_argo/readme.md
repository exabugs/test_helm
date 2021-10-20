# kustomize

```
kubectl kustomize hello01
```

## deploy

```
kubectl apply -k dev/overlays/hello01
kubectl apply -k dev/overlays/hello02
```

## delete

```
kubectl delete -k dev/overlays/hello01
kubectl delete -k dev/overlays/hello02
```
