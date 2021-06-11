# Official Henry County, Ohio Ansible Playbook
### Current Version v0.2a
**Maintained by Ryan Cohrs**

This is a ansible playbook that can be used to update all servers in the current infrastructure.  Not all servers are working yet and a list of server to get working can be see below.


### Task List
-   [x] Linux Server Updater
-   [ ] Windows Server Updater
-   [ ] First Release



### Servers
-   [x] Ryan Linux
-   [ ] DC Servers
-   [ ] SQL Servers
-   [ ] Courtview Servers
-   [ ] 2012 R2 Servers

## Host Installation Instructions

1.  Install Ansible on your control machine `pip install ansible`.
2.  Make at least one ssh connection normally to add the clients to your known_hosts file.
3.  (Optional) Set the python interpreter in your hosts file to `ansible_python_interpreter=/usr/bin/python`.
4.  Run the playbook in the project by running `ansible-playbook hc_playbook/playbooks/playbookname.yml -kK`.