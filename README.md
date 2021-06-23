# argocd-builder
This is a portable simulator of ArgoCD resource generation mechanism

### Build

```
make build
```


### Run

```
docker run --rm --volume <PATH/TO/ARGOCD_CONFIG>:/tmp/appconfig localhost:5000/argocd-builder:latest argocd-builder-core
```
