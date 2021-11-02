# Dependencies
Before using this ansible script, the user which runs the playbook must connect to te remote server trough the SSH keys
You can create this user as ansible user by executing the following command:
```bash
ansible-playbook create-ansible-user.yml -u root -K
```

# Usage
## Inventory
The make this ansible script work, you need to add the servers on the inventory files
inventorys/redhat
inventorys/ubuntu
inventorys/windows
```bash
ansible-playbook -i inventorys/redhat/nodes.yml site.yml 
```
