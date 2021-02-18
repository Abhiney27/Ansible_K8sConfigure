# Ansible_K8sConfigure

# There are three roles
* ec2_instance
* Kube_Master
* Kube_Slave

# . ec2_instance 
It is an Ansible role to launch three AWS EC2 Instances one would be for Kubernetes Master and other two would be for Kubernetes Slaves
To use this role you have to edit the variable file by going into vars folder, you have to give your access_key , secret_key , region_name , image_id , instance_type , vpc_subnet_id , security_group , key_name.

# . Kube_Master
It is an Ansible role to configure Kubernetes Master node 

# . Kube_Slave
It is an Ansible role to configure Kubernetes Slave nodes




