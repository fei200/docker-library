## docker-library

kubernetes 相关 images 同步

# 2018.6.7

v1.9.0
k8s dashboard 1.8.3

# 2018.5.24

## tensorflow-horovod
v1.9.0
* python: 3.5
* tensorflow-gpu: 1.6
* PYTORCH_VERSION: v0.4.0
* CUDNN_VERSION: 7.0.5.15-1+cuda9.0
* NCCL_VERSION : 2.2.12-1+cuda9.0

tf-1.6-sklearn: 基于官方Dockerfile，增加了sklearn，[Dockerfile](https://github.com/fei200/docker-library/commit/28ddf9ee354524047739f0e26598b5efc46e1915#diff-55958daa91a1f881a2ebb71245c134c0)

tf-1.6:  基于horovod官方Dockerfile，增加了ssh, [Dockerfile](https://github.com/fei200/docker-library/commit/e12cbd1bfd26ddecd396d7bc69e849fbd345e74f#diff-55958daa91a1f881a2ebb71245c134c0)

# 2018.1.2017

* 新增监控组件heapster v1.5.0
	
	包括两个目录:heapster-amd64和addon-resizer(addon-resizer:1.8.1)

# 2017.12.24
* 将kube的4个组件版本升级到1.9.0
* 将本文采用markdown格式书写
	
# 2017.12.23
* 删除无关的目录
* 新增目录kube-aggregator-amd64
	  
# 2017.12.23

	kube-apiserver-amd64:v1.8.4
	kube-controller-manager-amd64:v1.8.4
	kube-scheduler-amd64:v1.8.4
	kube-proxy-amd64:v1.8.4
	etcd-amd64:3.0.17
	pause-amd64:3.0
	k8s-dns-sidecar-amd64:1.14.5
	k8s-dns-kube-dns-amd64:1.14.5
	k8s-dns-dnsmasq-nanny-amd64:1.14.5
	flannel:v0.9.1-amd64
