Ansible role for setup metricbeat on elk clients.
=========

Metricbeat setup role on elk clients. This role include in default terraform scenario for auto-deploy new server.

-------

For manual installation this role on new client need install galaxy and run playbook:

```ansible-galaxy install tenantcloud.ansible_role_metricbeat```

Add this role name to playbook and run:

```cd /tmp/.ansible/ && ansible-playbook playbook-name.yml```

-------

Or in avaliable playbook add to hosts file new client IP address or hostname and run playbook.

-------

Variable included in this role:

-------

Sample playbook-name.yml

- hosts: localhost
  become: yes
  roles:
    - ansible-role-metricbeat

