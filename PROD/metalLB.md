# metalLB on Microk8s Cluster:
# Assigned IPs: 10.0.150.3 - 10.0.150.30
# Run this command to see the config of the MetalLB of the cluster
```microk8s kubectl get ipaddresspools -n metallb-system -o yaml```