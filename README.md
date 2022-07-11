vector-role
=========

Роль, создана из Playbook для задания 08.03 Roles - были вынесены tasks, vars, templates и handlers. Является частью работы над разделом по изучению Ansible.  

Requirements
------------

Role проверяется и настраивается для работы только на Ubuntu 20.04

Role Variables
--------------

| Variable | Descrition | Default value |
| ----- | ----- | ----- |
| vector_version | Версия vector для установки | "0.22.3-1" |

Dependencies
------------

Роль не использует зависимости с другими ролями.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install latest Vector
      hosts: localhost-vector
      roles:
         - vector-role

License
-------

MIT

Author Information
------------------

Vladimir Bakseev
