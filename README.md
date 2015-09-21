==========================
gutocarvalho-packer-centos6
==========================

Packer templates for building base VM boxes for Virtualbox.

Usage
=====

Installing Packer
-----------------

If you're using Homebrew

::

    $ brew tap homebrew/binary
    $ brew install packer


Running Packer
--------------

::

    $ git clone https://github.com/gutocarvalho/packer-centos6.git
    $ cd packer-centos6
    $ packer build packer.json

Supported versions
------------------

This templates was tested using a packer 0.8.6 .