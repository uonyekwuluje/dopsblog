## Ansible Kubernetes
Ansible Rancher Kubernetes Implementation
```
ansible -m ping rke2_stack -v -o
ansible-playbook playbooks/main.yml
```

### Test 
List Cluster Nodes `kubectl get nodes`:
``` 
NAME           STATUS   ROLES                       AGE    VERSION
kube-master    Ready    control-plane,etcd,master   146m   v1.20.7+rke2r2
kube-node-01   Ready    <none>                      72m    v1.20.7+rke2r2
kube-node-02   Ready    <none>                      72m    v1.20.7+rke2r2
```
