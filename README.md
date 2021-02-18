# Ansible_K8sConfigure

# There are three roles
* ec2_instance
* Kube_Master
* Kube_Slave

# ec2_instance 
It is an Ansible role to launch three AWS EC2 Instances one would be for Kubernetes Master and other two would be for Kubernetes Slaves.
To use this role you have to edit the variable file by going into vars folder, you have to provide the following :
* access_key , secret_key , region_name , image_id , instance_type , vpc_subnet_id , security_group , key_name.
This role uses dynamic inventory file for ec2 so , first you hav to create that . 

# Kube_Master
It is an Ansible role to configure Kubernetes Master node 

# Kube_Slave
It is an Ansible role to configure Kubernetes Slave nodes

# ansible.cfg
It is an Ansible configuration file

# ip.txt
It is an Inventory file where we put IP of all the Target node

# ec2_instance.yml
It is an Ansible playbook to run the the ec2_instance role.

# Master.yml
It is an Ansible playbook to run the Kube_Master role.

# Slave.yml 
It is an Ansible playbok to run the Kube_Slave role.







