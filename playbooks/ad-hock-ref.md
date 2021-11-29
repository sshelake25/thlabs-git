
-------------------------------------------------------
	1. Creating file by adhoc command 

Ansible -m file -a 'path=/tmp/surekha.txt state=present' all --syntax-check

-------------------------------------------------------------------
	1. Delete file by adhoc command 
	
Ansible -m file -a 'path=/tmp/surekha.txt state=absent' all

-------------- Creation of playbook ----------
ansible --version
ansible ungrouped --list-hosts
ansiblle dbweb --list-host
ansible -i filename dbsev --list-hosts


inside ansible.cfg file  