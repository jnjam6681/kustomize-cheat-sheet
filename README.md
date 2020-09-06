# Kustomize Cheat Sheet

## Kubectl
```
kubectl apply -k ./application/
```

## Kustomize
```
kustomize build .

kustomize edit set image [image_name]:[tag]
```
#### References
- [https://kubectl.docs.kubernetes.io/pages/reference/kustomize.html](https://kubectl.docs.kubernetes.io/pages/reference/kustomize.html)
- [https://kubectl.docs.kubernetes.io/pages/examples/kustomize.html](https://kubectl.docs.kubernetes.io/pages/examples/kustomize.html)
