# Ansible-Playbooks
PiTronica's ansible playbooks used in the PiTronica Tutorials


## Ansible-latest.yml

Installing ansible on your pi will set you back a few versions when using the standard raspberry repositories.
When ansible is already installed use this yml file to upgrade to the latest available.

running the playbook:

`wget https://raw.githubusercontent.com/PiTronica/Ansible-Playbooks/main/ansible_latest.yml`

`ansible-playbook ansible_latest.yml --extra-vars 'target=localhost'`
