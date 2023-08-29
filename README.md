Role Name
=========

Роль устанавливает и настраивает сервер LightHouse. Перед установкой сервера роль устанавливает пакеты epel-release, git и nginx


Role Variables
--------------

В роли нет изменяемых переменных.

Example Playbook
----------------

    - hosts: servers
      roles:
         - kmv879.lighthouse-role

License
-------

MIT

Author Information
------------------

------------------
Role by [Mikhail Kozhedub](https://github.com/kmv879).