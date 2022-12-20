```yaml
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: config-chart
  namespace: fleet-local
spec:
  repo: https://github.com/rancher/fleet-examples
  branch: test-helm-kustomize-disabled

  paths:
  - config-chart
```
