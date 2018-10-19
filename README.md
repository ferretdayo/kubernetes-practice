# 事前条件
- Dockerの環境がある
- kubernetesの環境がある

# 立ち上げ方
```
kubectl apply -f helloworld.deployment.yml
kubectl apply -f service.yml
```

その後， `http://localhost` にアクセス

## 操作方法
### pod達の状態を取得したい

```
kubectl get pods
```

### pod達の詳細情報を知りたい

```
kubectl describe pods [pod-name]
```

### deploymentsについていろいろ知りたい
```
kubectl get deployments
kubectl describe deployments
```

### serviceについていろいろ知りたい
```
kubectl get service
kubectl describe service
```