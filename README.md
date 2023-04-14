# iMC-ansible
Simple playbook of the initial server setup for installig H3C iMC. Installation of all necessary packages is done automatically on the basis of the official installation guide.
Before running network configuration shuld be done. Base image is CentOS-7-x86_64-DVD-1804.iso. Nothing to do here besides creating user with administrative rights.
In ansible-hosts and playbook.yaml files shoud be inserted correct IP and USERNAME
After playbook was finished - need to find mySQL password (placed in /var/log/messages and could be found with 'greep root@localhost')

