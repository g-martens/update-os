# Dependencies
Before using this ansible script, the user which runs the playbook must connect to te remote server trough the SSH keys
You can create this user as ansible user by executing the following command:
```bash
ansible-playbook create-ansible-user.yml -u root -K
```

# Inventory

