# Metrics Server - Patch to use with k3s cluster

[metrics-server](https://github.com/kubernetes-sigs/metrics-server) | [Why I need this patch?](https://github.com/kubernetes-sigs/kind/issues/398#issuecomment-1221698678)

### How to apply:

  1. `kubectl apply -k .` or `kustomize build . | kubectl apply -f -`