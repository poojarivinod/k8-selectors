## Selectors

# seach as k8 taints in google --> kubernetes
taint node

# kubectl get nodes --show-labels --> copy any node name
# Its meaning is not scheduling any pod to this node
# {ip-192-168-31-217.ec2.internal} is node name

```
kubectl taint nodes ip-192-168-31-217.ec2.internal hardware=gpu:NoSchedule
```
