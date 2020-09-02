# Echo-Service Deployment

Deployment a service named “echo-service” with a typical echo server image to
kubernetes in namespace echo-test.


#Prerequisites

* Kubectl

# Usage
Use the below command to deploy all of the related pod, ingress, service and deployment to the kubernetes cluster.

```bash
kubectl create -k deploy/
```


**NOTE: when you use kustomize you muster in the directory where exists kustomization.yaml**
