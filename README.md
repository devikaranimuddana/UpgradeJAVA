# UpgradeJAVA
UpgradeJAVA role consists of a playbook to upgrade Java on remote machine

- The main playbook to execute the role is java_upgrade.yml
- This role tasks are in the tasks directory main.yml playbook
- command to execute this playbook is 
   ANSIBLE_SCP_IF_SSH=y ansible-playbook -i /usr/local/ansible/inventories/hosts /usr/local/ansible/playbooks/java_upgrade.yml -e "hosts=xxxx"
