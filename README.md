# ansible-kubernetes-setup
Ansible playbooks to deploy and manage Kubernetes clusters on bare-metal/VMs.

## Playbooks
| Playbook | Purpose |
|----------|---------|
| `playbooks/prepare_nodes.yml` | Prepare RHEL nodes for Kubernetes |
| `playbooks/install_kubeadm.yml` | Install kubeadm/kubelet/kubectl |
| `playbooks/init_master.yml` | Initialize the control plane |
| `playbooks/join_workers.yml` | Join worker nodes to the cluster |
