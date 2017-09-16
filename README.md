Role Name
=========

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kazoo-ansible.rabbitmq, rabbitmq_user: user, rabbitmq_password: password }

License
-------

MIT

