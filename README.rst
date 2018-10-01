====================
ROLE passenger_nginx
====================

.. image:: https://img.shields.io/github/license/adfinis-sygroup/ansible-role-passenger_nginx.svg?style=flat-square
  :target: https://github.com/adfinis-sygroup/ansible-role-passenger_nginx/blob/master/LICENSE

.. image:: https://img.shields.io/travis/adfinis-sygroup/ansible-role-passenger_nginx.svg?style=flat-square
  :target: https://travis-ci.org/adfinis-sygroup/ansible-role-passenger_nginx

.. image:: https://img.shields.io/badge/galaxy-adfinis--sygroup.passenger_nginx-660198.svg?style=flat-square
  :target: https://galaxy.ansible.com/adfinis-sygroup/passenger_nginx

This role configures and manages the Passenginer NGINX web application server.


Requirements
=============

This role has no additional requirements.


Role Variables
===============

The following defaults variables can be configured:

.. code-block:: yaml

  # TODO


The following vars variables are set for Debian / Ubuntu and can be overwritten
if necessary:

.. code-block:: yaml

  # TODO


The following vars variables are set for RHEL / CentOS and can be overwritten if
necessary:

.. code-block:: yaml

# TODO


Dependencies
=============

This role has no additional dependencies.


Example Playbook
=================

Below example shows how the role can be integrated into a playbook using
external vars:

.. code-block:: yaml

  - hosts: servers
    roles:
       - { role: adfinis-sygroup.passenger_nginx }


License
========

`GPL-3.0 <https://github.com/adfinis-sygroup/ansible-role-passenger_nginx/blob/master/LICENSE>`_


Author Information
===================

passenger_nginx role was written by:

* Adfinis SyGroup AG | `Website <https://www.adfinis-sygroup.ch/>`_ | `Twitter <https://twitter.com/adfinissygroup>`_ | `GitHub <https://github.com/adfinis-sygroup>`_

