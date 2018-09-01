# Keepalived for Docker
Add your docker hosts to the host file and this playbook will update the settings on every host to share the virtual IP.
```
ansible-playbook keepalived.yml -i ./inventories/keepalived/hosts.ini
```

Or if you need to sudo:
```
ansible-playbook keepalived.yml -i ./inventories/keepalived/hosts.ini -b -K
```