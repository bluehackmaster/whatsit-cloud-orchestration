# whatsit-cloud-orchestration


### Exposing mongodb service
```sh
kubectl --namespace=whatsit expose service mongo --type=LoadBalancer --name=mongo-service
```
