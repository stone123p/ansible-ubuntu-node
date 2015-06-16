# ansible-ubuntu-node

------------------------

Ansible playbook for intalling Node.js on an Ubuntu 14.04 Server

*These playbooks require Ansible 1.8.1.*

The inventory file *hosts* defines the nodes in which the stacks should be configured.

```
        [host_group]
        host
```

Here the server would be configured on the host called "host".
The stack can be deployed using the following
command:

```
        ansible-playbook -i [hosts file] [site.yml file] 
```

