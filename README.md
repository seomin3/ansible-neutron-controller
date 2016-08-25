openstack-neutron
=================

**Status**
* [![Build Status](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron.svg?branch=master)](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron) on master branch
* [![Build Status](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron.svg?branch=development)](https://travis-ci.org/openstack-ansible-galaxy/openstack-neutron) on development branch

OpenStack Neutron Controller role


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
