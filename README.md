## Iac With Ansible:



## ![](Images/Ansible1.png)




### What is Ansible?
- Ansible is most popular automation tool used for managing infrastructure as code.

### Benefits:
- Open source tool
- Easy to setup
- Lots of plugins available
  

 ### How it works ?
- Multiple machines/servers can be managed by single machine called master controller or Ansible controller.
 - We need to download ansible into the master or controller machine and it can do everything for us in multiple other machines called hosts.


- if we want to download any dependencies on any number of machines, we can do it by running commands in just ansible controller.
- That saves lots of time, as we don't need to ssh into miltiple machine and do it manually.

- Ex: We can install nginx in web machine by running commands in Ansible controller machine and we don't need to ssh into web machine.
- After installing nginx in web VM, we can check the status of nginx from Ansible controller itself. No need to ssh into web machine.











![](Images/Ansibles.png)