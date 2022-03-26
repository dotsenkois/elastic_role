Elascticsearch role
=========

Роль для установки elasticsearch на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| elasticsearch_version | "8.1.1" | Параметр, который определяет какой версии elasticsearch будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: elastic_role }

License
-------

BSD


