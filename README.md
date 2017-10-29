andrewrothstein.trust-ca
========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-trust-ca.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-trust-ca)

Installs a certificate authority TLS certificate into the target system.

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
