# Deploy Nodejs application by Ansible

In this lab, we deploy a Nodejs application using Ansible. The steps we will complete the lab include:

1. Create an AWS EC2 instance for Ansible control node
2. Install Ansible on the instance
3. Create another EC2 instance for Node server
4. Write an Ansible Playbook
    - Install node & npm on server
    - Copy Node artifact and unpack
    - Start the application
    - Verify the application running properly


##  Install Ansible on Ubuntu
 
Ansible can be installed simply with the following commands:

```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```
