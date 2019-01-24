# ansible-role-devops-tools
Ansible role for installing DevOps tools on Linux machines (currently RedHat family only)

Sample playbook file (devops-tools.yml):

```
- hosts: localhost
  connection: local
  roles:
    - ansible-role-devops-tools
```
## tools installed by this role
- [helm](https://github.com/helm/helm)
- [heptio-authenticator-aws / aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator)
- [kops](https://github.com/kubernetes/kops)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/)
- [packer](https://www.packer.io)
- [serverless](https://serverless.com/framework/)
- [terraform](https://www.terraform.io)
- [vault](https://www.vaultproject.io)
