# ansible-ffdon
Ansible based server configuration

# how to clone
```bash
git clone git@github.com:ffdon/ansible-ffdon.git
cd ansible-ffdon
git submodule update --init roles

Anpassen:

 roles/gateways_l2tp/tasks/main.yml 
   iproute DURCH iproute2 ERSETZEN
   https://github.com/ffrl/tunneldigger gibt es nicht mehr ...

ansible-playbook -i hosts gateways.yml --ask-vault-pass --diff
```
