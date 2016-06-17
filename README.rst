cookiecutter-reclass-model
============================

A cookiecutter_ template for tcp cloud OpenStack infrastructure model full
possible setup.

.. _cookiecutter: https://github.com/audreyr/cookiecutter


Installation
============

.. code-block:: bash

    pip install cookiecutter

    cookiecutter cookiecutter-reclass-model


Parameters
----------

Following parameters need to be provided

* "project_name": "project-reclass-salt-model", name of
* "domain_name": "cloud.company.com", domain part of FQDN
* "apt_repository": "", APT repository base URL
* "apt_branch": "nightly", APT repository branch (nightly, testing, stable)
* "cfg01_name": "cfg01", hostnames
* "ctl01_name": "ctl01",
* "cmp01_name": "nod01",
* "cmp02_name": "nod02",
* "cmp03_name": "nod01",
* "cmp04_name": "nod02",
* "cmp05_name": "nod01",
* "cfg01_ip": "", IP addresses
* "ctl01_ip": "",
* "cmp01_ip": "",
* "cmp02_ip": "",
* "cmp03_ip": "",
* "cmp04_ip": "",
* "cmp05_ip": "",
* "service_ip_range": "10.150.0.0/16",
* "openstack_version": "kilo"