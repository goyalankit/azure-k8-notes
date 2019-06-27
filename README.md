# kubernetes

networking model:  https://kubernetes.io/docs/concepts/cluster-administration/networking/#kubernetes-model

1. pods on a node can communicate with all pods on all nodes without NAT
2. agents on a node (e.g. system daemons, kubelet) can communicate with all pods on that node
Note: For those platforms that support Pods running in the host network (e.g. Linux):
3. pods in the host network of a node can communicate with all pods on all nodes without NAT

Once can set networking policies as well using kubernetes:
https://kubernetes.io/docs/concepts/services-networking/network-policies/


