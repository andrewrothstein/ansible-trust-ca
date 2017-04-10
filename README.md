[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-trust-ca.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-trust-ca)
andrewrothstein.trust-ca
========================

Installs a CA certificate and trusts it

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: andrewrothstein.trust-ca
	  trust_ca_pki_dir: ~/pki
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
