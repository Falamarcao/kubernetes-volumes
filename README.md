# Kubernetes Volumes

## Environment Variables

We can set on deployment.yaml under the container configuration using the key `env` or using a `ConfigMap` in a new YAML file.

```sh
    kubectl apply -f host-pv.yaml,host-pvc.yaml,environment.yaml,deployment.yaml,service.yaml

    # Get Persistent Volumes
    kubectl get pv

    # Get Persistent Volumes Claims
    kubectl get pvc

    # Get ConfiMaps
    kubectl get configmap
```