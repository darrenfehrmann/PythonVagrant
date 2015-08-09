Python Vagrant Box
==================

Overview
--------

A vagrant box used for creating Django applications. Includes
a headless Selenium instance for functional testing.

Prerequisites
-------------

Provisioning is done via [Ansible](http://www.ansible.com),
which needs to be installed on the host machine.

[Vagrant](http://www.vagrantup.com) will need to be installed
as will [Virtualbox](http://www.virtualbox.org).

Installation Instructions
-------------------------

1. Install the prerequisites above.
2. Git clone this repo.
3. Run `vagrant up` from the repo root.
