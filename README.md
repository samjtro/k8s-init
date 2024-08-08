# k8s-init

from 0 to a k8s installation on a fresh ubuntu server instance. scripts deploy 3 multipass VMs on which ctrl plane + kubelets are housed. native k8s with the exception of calico for cni.

architecture:
```
Rhizome (ctrl-plane)
^               ^
|               |
Node1(kubelet) Node2(kubelet)
```
