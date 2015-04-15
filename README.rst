=============
Manila Images
=============

`Manila Images` is a small project to produce images which can be used
as base image for Manilas `generic driver`. The generic driver uses Nova
to spawn an instance and configures that instance to export shares.

Getting Started
---------------

If you'd like to run from the master branch, you can clone the git repo::

    git clone https://github.com/toabctl/manila-images.git

To create a Ubuntu 14.04 image which is used for testing and gating, do::

    sudo tox -e ubuntu-1404

This creates a new image in the `images` directory. The images is created via
`diskimage-builder <http://docs.openstack.org/developer/diskimage-builder/>`_.


More Information about Manila
-----------------------------

You have come across an OpenStack shared file system service.  It has
identified itself as "Manila." More information can be found at:

* Wiki: https://wiki.openstack.org/Manila
* Developer docs: http://docs.openstack.org/developer/manila

