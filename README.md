andrewrothstein.trust-ca
========================
![Build Status](https://github.com/andrewrothstein/ansible-trust-ca/actions/workflows/build.yml/badge.svg)

Installs a certificate authority TLS certificate into the target systems root trust store..

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
      trust_ca_configs:
        - name: my-pki
          pki_dir: ~/pki
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
