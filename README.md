# sidecar-dind
## 使用方式
参考微信公众号“云原生手记”中文章《Tekton CI 之实战篇（二）： DinD方式构建镜像》查看详情
运行:
```
docker build -t registru.nanjun/tekton/docker:v18.05-dind
```
去tekton集群运行
```
kubectl apply -f .
```
