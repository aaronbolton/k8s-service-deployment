# k8s-service-deployment

 a sample Kubernetes deployment and services to expose the pod via nodeport (not loadbalancer as this is only support by cloud provider AWS/Azure/GCS)

kubectl apply -f deployment.yaml

kubectl apply -f services.yaml

also a busybox.yaml deployment for executing commands within the cluster

e.g
     kubectl exec busybox -- nslookup nginx
