# Helm Chart for Backend!

This was the first Helm Chart created and it consider only the Backend. The following commands allows to create and verify the resource for Kubernetes, and as you might notice the environment variable NAME is passed through the install process:

```
helm create stakater-chart
helm lint .\stakater-chart
helm template .\stakater-chart
helm install --generate-name .\stakater-chart --set env.NAME="Stakater"
```
