# k8s-init

From 0 to an on-prem k8s instance. At the moment, scripts deploy Multipass VMs on which Ctrl Plane + Kubelets are housed. Using Calico as a CNI-addon, everything else is just straight kubernetes. 

'''Architecture diagram:
Rhizome (ctrl-plane)
^               ^
|               |
Node1(kubelet) Node2(kubelet)'''

You can add extra VMs for more kubelets, if neccesary. This project is supposed to be as pure, barebones of an install as possible. Again, the goal is for it to be modular. 
