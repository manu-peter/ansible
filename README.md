What is ansible and its use cases?

Ansible is an open source, command-line IT automation software application written in Python .

Ansible is used to automate IT tasks such as configuration management, application deployment, intraservice orchestration, and provisioning .

Ansible was created by Michael DeHaan at February 20, 2012 .

DeHaan initially developed Ansible as a side project while working at a software-defined networking company . 

He wanted to create a tool that would simplify and streamline the process of managing and automating configuration tasks across multiple servers .

Basic commands used in Ansible are . :

* ansible all -m ping --> This command uses the ping module to check the connectivity to all hosts defined in the inventory .

* ansible-playbook filename.yml --> This command runs the playbook filename.yml .

* ansible-inventory --list --> This command displays the current inventory in JSON format .

* ansible-config view --> This command shows the current configuration settings .

* ansible-playbook filename.yml --check --> This command performs a dry run of the playbook to see what changes would be made without actually applying them .

* ansible-playbook filename.yml --syntax-check --> This command checks the syntax of the playbook without running it .

* ansible-playbook filename.yml --list-tasks --> This command lists all tasks that would be executed in the playbook .
