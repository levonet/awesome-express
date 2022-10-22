# Deploying any service that provides an HTTP API

Example:

```sh
helm install test-api api --wait -n infrastructure --set image.name=levonet/nginx,image.tag=latest
helm ls -n infrastructure
helm uninstall test-api -n infrastructure
```
