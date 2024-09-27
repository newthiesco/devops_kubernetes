# devops_kubernetes

The following Kubernetes architecture diagram shows all the components of the Kubernetes cluster and how external systems connect to the Kubernetes cluster.

![alt cluster](images/k8_cluster.PNG)

The following image shows a high-level overview of how the scheduler works

![alt scheduler](images/k8_scheduler.PNG)

CNI Plugin enables networking between pods spread across the same or different nodes using an overlay network
Following are high-level functionalities provided by CNI plugins.

1- Pod Networking
2- Pod network security & isolation using Network Policies to control the traffic flow between pods and between namespaces

Some popular CNI plugins include:

Calico
Flannel
Weave Net
Cilium (Uses eBPF)
Amazon VPC CNI (For AWS VPC)
Azure CNI (For Azure Virtual network)Kubernetes networking is a big topic and it differs based on the hosting platforms.

When it comes to networking, the following Kubernetes objects plays a key role.

Services
Ingress
Network policies.

![alt k8_overlay_network](images/overlay_networking.PNG)


