This is a basic setup for my VPS server.

```
ansible-playbook -i inventory.ini playbook.yml --extra-vars "tailscale_auth_key=<auth_key>"
```
add -u root

if you run as root.

