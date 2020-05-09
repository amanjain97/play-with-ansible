## Setup 
1. Add ssh key to the remote machine. 
2. Change IP of host or FQDN in inventory/hosts
3. Update playbooks/playbook.yaml 

## How to run
```bash
$ ansible-playbook -i inventory/hosts playbooks/playbook.yaml
```

## What if things didnot work out for you ?
You can run in debug mode 
```bash
$ ansible-playbook -i inventory/hosts playbooks/playbook.yaml -vvv 
```
