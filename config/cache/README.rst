The buildout config here will help you compile, build, configure
the following cache Servers for your application.
The corresponding supervisor_ config file will be generated for
each server.

What we have
------------

Here are the list of cache servers we covered:

- redis_ and phpredis_ extension
- memcached_
- varnish_

Stories
-------

- `Varnish Story <Varnish-Story.rst>`_

Samples
-------

Check the `cache sample folder <../../sample/cache>`_ for 
some typical use cases.

.. _supervisor: https://github.com/Supervisor/supervisor
.. _redis: http://redis.io
.. _phpredis: https://github.com/nicolasff/phpredis
.. _memcached: http://memcached.org/
.. _varnish: https://www.varnish-cache.org/
