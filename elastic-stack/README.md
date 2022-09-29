1. 구성
```code
kubectl apply -f elasticsearch-definition.yaml
kubectl apply -f kibana-definition.yaml
kubectl apply -f fluentd-daemonset-definition.yaml
```

2. 확인
```code
kubectl get all -n elastic-stack
```
