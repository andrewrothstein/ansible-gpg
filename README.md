andrewrothstein.gpg
=========
![Build Status](https://github.com/andrewrothstein/ansible-gpg/actions/workflows/build.yml/badge.svg)

Installs [gpg](https://www.gnupg.org/) from OS packages.

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
    - andrewrothstein.gpg
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
