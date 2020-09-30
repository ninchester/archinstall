.. _installing.python:

Python library
==============

Archinstall shipps on `PyPi <https://pypi.org/>`_ as `archinstall <pypi.org/project/archinstall/>`_.
But the library can be installed manually as well.

Using PyPi
----------

The basic concept of PyPi applies using `pip`.
Either as a global library:

.. code-block::

    sudo pip install archinstall

Or as a user module:

.. code-block::

    pip --user install archinstall

Which will allow you to start using the library.

.. _installing.python.manual

Manual installation
-------------------

You can either download the github repo as a zip archive.
Or you can clone it, we'll clone it here but both methods work the same.

.. code-block::

    git clone https://github.com/Torxed/archinstall

Either you can move the folder into your project and simply do

.. code-block:: python

    import archinstall

Or you can use `setuptools <https://pypi.org/project/setuptools/>`_ to install it into the module path.

.. code-block::

    sudo python setup.py install