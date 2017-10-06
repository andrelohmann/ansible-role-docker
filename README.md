docker
======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-docker.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-docker)

Deploy docker and docker users to your machine

Role Variables
--------------

Create a list with all users that need to be added to the docker group

    docker_users:
    - __USERNAME__
    - __OTHER_USERNAME__

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: docker
      roles:
         - { role: andrelohmann.docker }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
