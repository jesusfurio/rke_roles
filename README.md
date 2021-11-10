# RKE Ansible roles
Ansible roles to deploy a single node RKE and RKE cluster.

# Introduction

This [Ansible](https://www.ansible.com/) role installs [RKE](https://rancher.com/docs/rke/latest/en/) in a VM. You can deploy a single node or a cluster with multinode.

## Deploy
It´s necessary to modify the path where the role is located in the playbook files (deploy-rke-cluster.yml and deploy-rke.yml).
* Single node
```bash
ansible-playbook /playbooks_path/deploy-rke.yml -i /inventorypath/inventory_name
```
* Multinode
```bash
ansible-playbook /playbooks_path/deploy-rke-cluster.yml -i /inventorypath/inventory_name
```