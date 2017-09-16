RabbitMQ
========

Kazoo Ansible role for RabbitMQ

Requirements
------------

None

Role Variables
--------------

User Variables
- rabbitmq_user - The user that will be used for RabbitMQ
- rabbitmq_password - The password that will be used for RabbitMQ

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible.rabbitmq, rabbitmq_user: user, rabbitmq_password: password }

License
-------

MIT

