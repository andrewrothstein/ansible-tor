andrewrothstein.tor
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-tor.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-tor)

Builds and installs [tor](https://www.torproject.org/) from source.

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
    - andrewrothstein.tor
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
