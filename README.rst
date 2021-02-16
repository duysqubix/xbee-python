Unofficial Digi XBee Python library |pypiversion| |pythonversion|
======================================================

This project contains the source code of the XBee Python library, an
easy-to-use API developed in Python that allows you to interact with Digi
International's `XBee <https://www.digi.com/xbee>`_ radio frequency (RF)
modules.

This source has been contributed by Digi International and outside volunteers.

Why Another Repo?
------------
The unofficial repository was spawned due to four main reasons that lacked in the official repository.

1. Outdated releases and pypi packages. Latest release and current master branch are seperated by over 250 commits.

2. Lack of activity by moderators regarding issues and open PR's. Some PR's date back to late 2019 with no activity, despite community reaching out. This causes a loss of interest in the project and fewer contributors.

3. Breaking the barrier of bureaucracy and allowing the continued effort of this library to be extended by the direct help of the community.

4. See 1 & 2.

This by no means is a jab, stab, or otherwise, insult at Digi. They have done an amazing work (so far) with the library. All the credit goes to them for this. 
I have seen in the community the struggles of folks who would like to contribute, but their voices are not heard or even looked at. Whatever the reason,
this repository aims to branch from the official repo so folks from the community can contribute and extend this library to its fullest potential.


Installation
------------

You can install the Unofficial XBee Python library using `pip
<https://pip.pypa.io/en/stable/>`_::

    $ pip install digi-xbee-unofficial


Install from Source
-------------------

You can install Unofficial XBee Python library directly from the source file. To do
so, extract the source code to your computer and, from its root
directory, execute the following command::

    $ python setup.py install


Documentation
-------------

The Unofficial XBee Python library has user guide and API reference documentation hosted on
Read the Docs. You can find the latest, most up to date, documentation at
`latest docs <https://xbplib.readthedocs.io/en/latest/>`_. To see only those
features which have been released, check out the
`stable docs <https://xbplib.readthedocs.io/en/stable/>`_.


How to contribute
-----------------

The contributing guidelines are in the `CONTRIBUTING.rst document
<https://github.com/duysqubix/xbee-python/blob/master/CONTRIBUTING.rst>`_.


License
-------

Copyright 2017-2021, Digi International Inc.

The `MPL 2.0 license <https://github.com/digidotcom/xbee-python/blob/master/LICENSE.txt>`_
covers the majority of this project with the following exceptions:

* The `ISC license <https://github.com/digidotcom/xbee-python/blob/master/examples/LICENSE.txt>`_
  covers the contents of the examples directory.

.. |pypiversion| image:: https://badge.fury.io/py/digi-xbee.svg
    :target: https://pypi.org/project/digi-xbee/
.. |pythonversion| image:: https://img.shields.io/pypi/pyversions/digi-xbee.svg
    :alt: PyPI - Python Version
