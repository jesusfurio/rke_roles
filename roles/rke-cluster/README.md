RKE Single Node
=========

An Ansible role that setup development Kubernetes cluster with RKE on Ubuntu and OpenSUSE.

Requirements
--------------
Inventory file with server IP in group calling "cluster".

Role Variables
--------------

* rke_cluster_name: Cluster name.
* rke_version: v1.3.1 by default. Defines RKE version.
* rke_binary_url: Defines RKE binary URL.
* rke_user: rke by default. User that will be used to connect on nodes during the installation process.
* rke_cluster_network_cidr: 10.42.0.0/16 by default. CIDR pool used to assign IP addresses to pods in the cluster.
* rke_service_network_cidr: 10.43.0.0/16 by default. This is the virtual IP address that will be assigned to services created on Kubernetes.

License
-------

Mit
