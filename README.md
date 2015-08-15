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

The box uses ssh agent forwarding to access the ssh keys on the host machine.
Before trying to hit git on the guest machine, you'll need to set up
your ssh agent forwarding on the host machine. Follow the instructions
on [coderwall.com](https://coderwall.com/p/p3bj2a/cloning-from-github-in-vagrant-using-ssh-agent-forwarding)

If you want to read more in-depth about ssh agent forwarding, see the article
on [unixwiz.net](http://www.unixwiz.net/techtips/ssh-agent-forwarding.html).

Installation Instructions
-------------------------

1. Install the prerequisites above.
2. Git clone this repo.
3. Run `vagrant up` from the repo root.
