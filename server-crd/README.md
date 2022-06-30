# server crd

此组件主要用于把各种服务器信息记录到k8s中。前期主要通过yaml apply来录入信息。后面可通过server-operator 调用各个云平台的接口，实现服务器的增删改查。


## 字段
```
hostname
ip
sshkey
type
```