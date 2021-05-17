================================
python-anyconfig-bson-backend
================================

.. image:: https://img.shields.io/pypi/v/anyconfig-bson-backend.svg
   :target: https://pypi.python.org/pypi/anyconfig-bson-backend/
   :alt: [Latest Versbson]

.. image:: https://github.com/ssato/python-anyconfig-bson-backend/workflows/Tests/badge.svg
   :target: https://github.com/ssato/python-anyconfig-bson-backend/actions?query=workflow%3ATests
   :alt: [Github Actions: Test status]

.. image:: https://img.shields.io/coveralls/ssato/python-anyconfig-bson-backend.svg
   :target: https://coveralls.io/r/ssato/python-anyconfig-bson-backend
   :alt: Coverage Status

.. image:: https://scrutinizer-ci.com/g/ssato/python-anyconfig-bson-backend/badges/quality-score.png
   :target: https://scrutinizer-ci.com/g/ssato/python-anyconfig-bson-backend
   :alt: [Code Quality by Scrutinizer]

.. landscape looks stopped their service.
.. .. image:: https://landscape.io/github/ssato/python-anyconfig-bson-backend/master/landscape.png
   :target: https://landscape.io/github/ssato/python-anyconfig-bson-backend/master
   :alt: Code Health

This is a backend module for python-anyconfig to load and dump BSON files using
pymongo.

- Author: Satoru SATOH <satoru.satoh@gmail.com>
- License: MIT

SEE ALSO:

- python-anyconfig: https://pypi.python.org/pypi/anyconfig/
- pymongo: https://pypi.python.org/pypi/pymongo/
- BSON spec: http://bsonspec.org

.. [#] bson from pymongo package may work and bson, https://pypi.python.org/pypi/bson/, does not.

Build & Install
================

- Pre-built Binary RPMs from my copr repos, https://copr.fedoraproject.org/coprs/ssato/python-anyconfig/

  ::

    # Example commands to install pre-built RPMs
    $ sudo dnf copr enable ssato/python-anyconfig
    $ sudo dnf install -y python3-anyconfig-bson-backend

- PyPI: pip3 install anyconfig-bson-backend
- pip from git repo: pip3 install git+https://github.com/ssato/python-anyconfig-bson-backend/
- Build SRPMs, RPMs and install it: python3 setup.py bdist_rpm --source-only && mock dist/python3-anyconfig-\*-backend-<ver_dist>.src.rpm
- Others: try usual ways to build and/or install python modules such like 'python3 setup.py bdist', etc.

.. vim:sw=2:ts=2:et:
