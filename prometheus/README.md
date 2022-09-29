1. configmap 생성
```code
kubectl create configmap prometheus --from-file=./prometheus-config.yaml
```
2. prometheus pod 생성
```code
kubectl apply -f prometheus-deployment.yaml
```
