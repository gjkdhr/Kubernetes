# Kubernetes
K8S 一些概念理解文档，也会尝试写一些yaml文件；

参考链接：
https://github.com/kubernetes-up-and-running/examples

k8s_volume   与kubernetes存储相关的资源创建;

kuard-emptyDir-volume.yaml	pod创建空目录存储emptyDir的实例;

kuard-hostPath-volume.yaml	pod绑定本地文件系统hostPath的实例;

kuard-nfs-pvc-test.yaml		利用nfs文件系统创建PersistentVolumeClam的简单实例过程;

kuard-nfs-volume.yaml		利用nfs文件系统生成PersistentVolume的实例;

kuard-pvc-volume.yaml		绑定nfs生成的pv，并将pvc挂载到pod容器中实例;
