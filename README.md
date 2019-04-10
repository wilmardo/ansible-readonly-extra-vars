# ansible-readonly-extra-vars

Demonstration of the readonly extra-vars.

# Expected behaviour:
```
ansible-playbook playbook-vars/playbook.yml
```

# Actual behaviour
```
ansible-playbook -e @extra-vars/vars.yml extra-vars/playbook.yml
```
