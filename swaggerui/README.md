# Setup

```
kubectl create configmap nginx-config --from-file nginx-reverseproxy.conf
kubectl create -f swaggerui-secrets.yml
kubectl create -f swaggerui-deployment.yml
kubectl create -f swaggerui-service.yml
```
