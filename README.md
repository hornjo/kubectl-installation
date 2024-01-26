Role Name
=========

Installation of kubectl with autocompletion.

Requirements
------------

Non air gapped system.

Role Variables
--------------

```BASH
kubectl_version: "v1.25.0" # Option to set the specific version, if not defined, lastest one will be used
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```YAML
- hosts: localhost
  roles:
    - kubectl-installation

```

License
-------

BSD

Author Information
------------------

<https://github.com/hornjo>
