labpositiva/ruby-node:6.10.0
============================

|Build Status| |GitHub issues| |GitHub license|

Requirements
------------

None

Dependencies
------------

none

Usage
-----

In order to run a basic container start a container as follows:

``docker run -P --name ruby-node -e ENV=DEV labpositiva/ruby-node:6.10.0``

Environment Variables
---------------------

This is a list of the available environment variables which can be set
at runtime using -e KEY=value. For example, to change the default
environment you can issue
``docker run -P --name ruby-node -e ENV=dev labpositiva/ruby-node:6.10.0``

.. |Build Status| image:: https://travis-ci.org/labpositiva/docker-ruby-node.svg
   :target: https://travis-ci.org/labpositiva/docker-ruby-node
.. |GitHub issues| image:: https://img.shields.io/github/issues/labpositiva/docker-ruby-node.svg
   :target: https://github.com/labpositiva/docker-ruby-node/issues
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE
