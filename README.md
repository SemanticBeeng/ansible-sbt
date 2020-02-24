semanticbeeng.ansible_sbt
=================

Installs [sbt](http://www.scala-sbt.org/) and bootstraps the compiler front-end.

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
    - semanticbeeng.ansible_sbt
```

License
-------

MIT

Author Information
------------------

(originally) Andrew Rothstein <andrew.rothstein@gmail.com>
