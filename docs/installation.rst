.. include:: global.rst.inc
.. _installation:

Installation
============

|project_name| requires Python_ 3.2 or above to work. Even though Python 3 is
not the default Python version on most Linux distributions, it is usually
available as an optional install.

Other dependencies:

* `msgpack-python`_ >= 0.1.10
* OpenSSL_ >= 1.0.0

The OpenSSL version bundled with Mac OS X and FreeBSD is most likey too old.
Newer versions are available from homebrew_ on OS X and from FreeBSD ports.

The llfuse_ python package is also required if you wish to mount an
archive as a FUSE filesystem.

Installing from PyPI using pip
------------------------------
::

    $ pip install Attic

Installing from source tarballs
-------------------------------
.. parsed-literal::

    $ curl -O |package_url|
    $ tar -xvzf |package_filename|
    $ cd |package_dirname|
    $ python setup.py install

Installing from git
-------------------
.. parsed-literal::

    $ git clone |git_url|
    $ cd attic
    $ python setup.py install

Please note that when installing from git, Cython_ is required to generate some files that
are normally bundled with the release tarball.

Packages
--------

|project_name| is also part of the Debian_, Ubuntu_, `Arch Linux`_ and Slackware_
distributions of GNU/Linux.
