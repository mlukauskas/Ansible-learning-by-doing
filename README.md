# Ansible-learning-by-doing
Simple project to learn Ansible. 

Provisioning VMware virtual machines with Ansible.

hosts - My Inventory File

[lbserver]
loadbalancer ansible_host=192.168.219.129

[webservers]
web01 ansible_host=192.168.219.130
web02 ansible_host=192.168.219.131
web03 ansible_host=192.168.219.132

[databaseservers]

Playbooks

site.yaml

roles

centos-apache  centos-nginx  centos-php  update-yum





