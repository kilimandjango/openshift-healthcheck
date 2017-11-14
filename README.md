**OpenShift Health Check**
========================================================
 This is a basic healtch check for an OpenShift Cluster. Probably 'oadm diagnostics' gives you a more complex summary of your cluster but it is well suited to understand your architecture. 
 The health check is an Ansible playbook which can be executed wherever Ansible is installed.
  
How to use the playbook
------------------
 - Check where your inventory file is located:
 `$ cat /etc/ansible/hosts`
 
 - Run the playbook:
 `$ ansible-playbook healtchcheck.yaml`
