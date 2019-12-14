# ansible-ffdon
Ansible based server configuration

# how to clone
```bash
git clone git@github.com:ffdon/ansible-ffdon.git
cd ansible-ffdon
git submodule update --init roles
ansible-playbook -i hosts gateways.yml --ask-vault-pass --diff
```
