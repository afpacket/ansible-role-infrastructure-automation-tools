# devops-tools-role
Ansible role for installing DevOps tools on Linux machines (currently RedHat family only)

Sample playbook file (devops-tools.yml):

```
- hosts: localhost
  connection: local
  roles:
    - ansible-role-devops-tools
```
