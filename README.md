# Helm Chart

Helm Chart 仓库

- 更新 chart

```shell
# 打包复制到本项目
helm package etcd/

# 重建 index.yaml
helm repo index --url https://mings135.github.io/chart .
```



- 添加 chart

```shell
# 添加本仓库
helm repo add ming https://mings135.github.io/chart
```

