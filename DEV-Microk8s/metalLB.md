# metalLB on Microk8s Cluster:
# Assigned IPs: 10.0.100.2 - 10.0.100.35
# Run this command to see the config of the MetalLB of the cluster
```microk8s kubectl get ipaddresspools -n metallb-system -o yaml```


# 10.0.100.2  - PiHole DNS
# 10.0.100.3  - PiHole DNS MGMT
# 10.0.100.5  - Nginx
# 10.0.100.14 - grafana
# 10.0.100.15 - influxdb 
# 10.0.100.21 - jellyfin
# 10.0.100.22 - Plex
# 10.0.100.30 - heimdall
# 10.0.100.31 - homarr



# metalLB on Microk8s Cluster - MGMT VLAN NICs:
# vmus-test-k8s-04 MGMT = 10.0.250.200
# vmus-test-k8s-05 MGMT = 10.0.250.201
# Assigned IPs: 10.0.250.210 - 10.0.250.220
# 10.0.250.210 - PiHole DNS
# 10.0.250.215 - Plex
