# Screenshots for the <br>_Microservices project submission_

## 1) Deployment Pipeline
- TravisBuild-1_9.png
- TravisBuild-2_9.png
- TravisBuild-3_9.png
- TravisBuild-4_9.png
- TravisBuild-5_9.png
- TravisBuild-6_9.png
- TravisBuild-7_9.png
- TravisBuild-8_9.png
- TravisBuild-9_9.png
- DockerImages.png

## 2) Kubernetes

<br>
<br>

***
***
# _Original documentation below_

<br>

# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
