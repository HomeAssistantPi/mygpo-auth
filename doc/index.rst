.. gpodder.net Auth documentation master file, created by
   sphinx-quickstart on Mon May 11 21:46:52 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

gpodder.net Auth
================

This is an OAuth 2 authorization server that will be used for authenticating
client applications for gpodder.net.

**The current API of gpodder.net does not yet support OAuth 2.**

HTTP Basic Auth is currently the only supported authentication mechanism. (see
`documentation <http://gpoddernet.readthedocs.org/en/latest/api/index.html>`_)


Test Instance
-------------

The Test instance uses the following endpoints:

* `Authorization Endpoint <http://tools.ietf.org/html/rfc6749#section-3.1>`_:
  ``https://mygpo-auth-test.herokuapp.com/oauth2/authorize``
* `Token Endpoint <http://tools.ietf.org/html/rfc6749#section-3.2>`_:
  ``https://mygpo-auth-test.herokuapp.com/oauth2/token``

Contents
--------

.. toctree::
   :maxdepth: 2

   register
   oauth-flow
   scopes
   token-info
   RFC 6749 <http://tools.ietf.org/html/rfc6749>
   GitHub <https://github.com/gpodder/mygpo-auth>
   Travis-CI <https://travis-ci.org/gpodder/mygpo-auth/>
   Coveralls <https://coveralls.io/r/gpodder/mygpo-auth>


Indices and tables
------------------

* :ref:`genindex`
* :ref:`search`
