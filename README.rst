toolchains feeds for Aldebaran pre-compiled packages
=====================================================

This is useful when you wan to compile (or
cross-compile) Aldebaran projects and you are OK
using our pre-compiled versions of the 3rd party libraries
we are using.

Requirements
-------------

``qibuild >= 3.11``. Can be installed via ``pip`` and available
on `Pypi <https://pypi.python.org/pypi/qibuild>`_


Usage
-----

To create a toolchain, look at the ``feeds`` directory for available
architectures and run::

  qitoolchain create --name <name> --branch <branch> git://github.com/aldebaran/toolchains.git

When ``<name>`` if the basename of a XML file in the ``feeds`` directory
and ``<branch>`` is a branch of this repository
