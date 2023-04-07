# lancache-ansible-playbook
Ansible playbook for setting up a lancache VM


# Setup prerequisites

## Install Python/pip

## Install Ansible
```
pip install ansible
```

## Copy Inventory
Copy the inventory file example and change what you need
```
cp inventory{.example,}
```

# Run

## Apply playbook with the following:
```
ansible-playbook app.yml --ask-become-pass
```
