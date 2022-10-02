# lancache-ansible-playbook
Ansible playbook for setting up a lancache VM


# Setup prerequisites

## Install Python/pip

## Install Ansible
```
pip install ansible
```

# Run

## Apply playbook with the following:
```
ansible-playbook -i inventory/all -v playbooks/app.yml --ask-become-pass
```
