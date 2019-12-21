Bootstrapping the Kubernetes Worker Nodes
=========================================

In this lab you will bootstrap three Kubernetes worker nodes. The following components will be installed on 
each node: runc, gVisor, container networking plugins, containerd, kubelet, and kube-proxy.

Provisioning a Kubernetes Worker Node
=====================================
sudo apt-get update
sudo apt-get -y install socat conntrack ipset
sudo apt install docker.io

The socat binary enables support for the kubectl port-forward command.


