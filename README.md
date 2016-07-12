# Ansible project template role
## Introduction
This role allow ansible newbies to create a standard project structure as explain below
> [Ansible best practices ](http://docs.ansible.com/ansible/playbooks_best_practices.html)

## Examples of using the role
Create the initial structure on the path /mnt/mboufnichel/ with the the role hybris

```bash
ansible-playbook -i hosts site.yml --extra-vars "brole=hybris bpath=/mnt/mboufnichel/"
```
## Add a new role “junit” to the previous structure
```bash
ansible-playbook -i hosts site.yml --extra-vars "brole=junit bpath=/mnt/mboufnichel/" --tags trole
```

## License

GNU General Public License v3.0
