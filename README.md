# Universal chart
Generic help chart to put any container payload to K8s

# Build
```
helm registry login registry.example.com

helm package charts/universal

helm push universal-*.tgz oci://registry.example.com/helm/universal
```