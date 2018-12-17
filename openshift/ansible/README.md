# Ansible playbooks

## Examples

```
ansible-playbook  --ask-vault-pass -e id=os1  configure.yaml
```

Note! os1 is a part of domain name like master.os1.demo.li9.com

## vars.yaml

All secrets are stored in vars.yaml. You may create your own vars.yaml

```
redhat_username: changme
redhat_password: changme
aws_access_key: changeme
aws_secret: changeme
ldap_password: changeme
```
