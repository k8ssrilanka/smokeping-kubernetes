# smokeping-kubernetes
YAMLs required to get Smokeping going on Kubernetes. Ideal for running Smokeping on Raspberry Pi with k3s.

# Inspried by the Smokeping Project 
Ref: [Smokeping Project] (https://oss.oetiker.ch/smokeping/)
Ref: [Linuxserver.io Dockerised Images] (https://hub.docker.com/r/linuxserver/smokeping)

### Prerequisits:
You have a running k8s or k3s cluster

### Following changes may be required before you apply the yamls
1. path to your storage. I am using attached media replace path: /media/usb-cruzer/smokeping-config with yours
2. size of your storage. I have given 2GB more than sufficient for a home configuration
3. your workload node if you are using more than one node. Modify nodeAffinity 
