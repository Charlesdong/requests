How to Help
===========

Requests is under active development, and contributions are more than welcome!

#. Check for open issues or open a fresh issue to start a discussion around a feature idea or a bug.
   There is a Contributor Friendly tag for issues that should be ideal for people who are not very
   familiar with the codebase yet.
#. Fork `the repository <https://github.com/kennethreitz/requests>`_ on Github andstart making your
   changes to a new branch.
#. Write a test which shows that the bug was fixed or that the feature works as expected.
#. Send a pull request and bug the maintainer until it gets merged and published. :)
   Make sure to add yourself to `AUTHORS <https://github.com/kennethreitz/requests/blob/master/AUTHORS.rst>`_.

Development Dependencies
------------------------

You'll need to install py.test in order to run the Requests' test suite::

    $ make test-deps
    $ make test
    py.test
    platform darwin -- Python 2.7.3 -- pytest-2.3.4
    collected 25 items

    test_requests.py .........................
    25 passed in 3.50 seconds

Runtime Environments
--------------------

Requests currently supports the following versions of Python:

- Python 2.6
- Python 2.7
- Python 3.1
- Python 3.2
- Python 3.3
- PyPy 1.9

Support for Python 3.1 and 3.2 may be dropped at any time.

Google App Engine will never be officially supported. Pull requests for compatiblity will be accepted, as long as they don't complicate the codebase.


Are you crazy?
--------------

- SPDY support would be awesome. No C extensions.
