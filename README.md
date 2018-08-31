# Locally Provioned Kuberetes Cluster with Anisble and Vagrant

This is an inteded demonstration of what can be done to quickly provision a local development environment utilizing the following tools:

1. [Kubernetes](https://kubernetes.io/)
2. [Vagrant](https://www.vagrantup.com)
3. [Ansible](https://www.ansible.com/)

The goal of this lab is to encourage experimentation on a small Kubernbetes environment and enable users to rapidly iterate on tasks and ideas without worring about long setup times or external provisioning dependencies. 

This lab assumes that you have a functional [virtual box](https://www.virtualbox.org/) and [Vagrant](https://www.vagrantup.com) setup on your local machine and at least 8 Gb of memory on your system. It also assumes a cursory knowledge of host based networking and the utilization of command line tools, as well as a functional knowledge of kubernetes. 

### Getting Started

Start by cloning this repo to your local machine and running 
```bash
vagrant up
```
This will begin the provisioning cycle for 3 Centos 7 nodes, a master node and 2 worker nodes. They will have the following hostnames and ipaddresses:

* **node1 172.17.8.101**
* **node2 172.17.8.102**
* **node3 172.17.8.103**



