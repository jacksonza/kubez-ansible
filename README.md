# Kubez-ansible Overview

Kubez-ansible's mission statement is:

    To provide quick deployment tools for kubernetes cluster.


### 环境部署
This session has been tested on CentOS 7 and python2.7 only.

- [测试环境](doc/source/install/all-in-one.md)

- [生产环境](doc/source/install/multinode.md)

### 环境维护

- [认证文件](doc/source/install/admin-k8src.md)

- [节点扩容](doc/source/install/expansion.md)

- [清理集群](doc/source/install/destroy.md)

### Supported Applications

#### CNI
  - `Flannel`
  - `Calico`

#### CRI
  - `docker`
  - `containerd`

#### Addon Applications
  - `Nginx Ingress`
  - `Helm3`
  - `Prometheus`
  - `Ceph provisioner`
  - `Nfs provisioner`

Copyright 2019 caoyingjun (284224086@qq.com) Apache License 2.0
