Subscribers
===========

The following variables are available in your templates:

* csrf_token
* csrf_token_field - though it contains the complete html, you may need to
  safe quote/raw the field. In Mako, ${csrf_token_field|n}
* flash methods are provided to access this for Mako/Jinja, but, if you
  want to access it directly, it is available.
