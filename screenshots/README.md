# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* [DockerHub showing containers that you have pushed](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-1-dockerhub-images.jpg)
* [GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-2b-travis-github-integration.jpg)
* [Travis CI showing a successful build and deploy job](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-2a-travis-build-history.jpg)

## Kubernetes
* [To verify Kubernetes pods are deployed properly](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-4-get-pods.jpg)
```bash
kubectl get pods
```
* [To verify Kubernetes services are properly set up](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-3-deployments.jpg)
```bash
kubectl describe services
```
* [To verify that you have horizontal scaling set against CPU usage](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-8-describe-hpa.jpg)
  [modified screen capture](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-11-describe-hpa.jpg)
```bash
kubectl describe hpa
```
* [To verify that you have set up logging with a backend application](https://github.com/rrprajiv/udagram-microservice/blob/main/screenshots/exhibit-9-backend-logs.jpg)
```bash
kubectl logs {pod_name}
```
