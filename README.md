# Official Henry County, Ohio IT Ansible Playbook
### Current Version v0.3a
_**Maintained by Ryan Cohrs**_

This is a ansible playbook that can be used to update all servers in the current infrastructure.  Not all servers are working yet and a list of server to get working can be see below.


### Task List
-   [x] Linux Server Updater
-   [ ] Windows Server Updater
-   [ ] First Release



### Servers
-   [x] Ryan Linux Servers
-   [x] County Linux Servers
-   [ ] DC Servers
-   [ ] SQL Servers
-   [ ] Courtview Servers
-   [ ] 2019 Servers
-   [ ] 2016 Servers
-   [ ] 2012 R2 Servers

### Host Installation Instructions

1.  Install [Python](https://docs.python-guide.org/starting/install3/linux/)
2.  Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on your control machine `pip install ansible`.
3.  Make at least one ssh connection normally to add the clients to your known_hosts file.
4.  (Optional) Set the python interpreter in your hosts file to `ansible_python_interpreter=/usr/bin/python`.
5.  Run the playbook in the project by running `ansible-playbook hc_playbook/playbooks/playbookname.yml -kK`.