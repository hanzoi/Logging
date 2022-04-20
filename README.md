# Logging
参考资料：
[https://kubernetes.io/zh/docs/concepts/cluster-administration/logging/](https://kubernetes.io/zh/docs/concepts/cluster-administration/logging/)

Kubernetes 三种日志方案
采用日志系统：Promtail + Loki + Grafana

1.用在每个节点上运行的节点级日志记录代理
2.在应用程序的 Pod 中，包含专门记录日志的边车（Sidecar）容器
3.将日志直接从应用程序中推送到日志记录后端
