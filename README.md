openstack-neutron-controller
=================

**Status**
* [![Build Status](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron-controller.svg?branch=master)](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron-controller) on master branch

OpenStack Neutron controller role


Requirements
------------

A RabbitMQ server.

A MySQL server.


Role Variables
--------------


Dependencies
------------

ansible-repos


Example Playbook
----------------

    - hosts: controller001
      roles:
        - role: openstack-neutron-controller
          (...)



License
-------

Apache

Author Information
------------------

Abel Boldú <abel.boldu@gmx.com>
