Psycopg
=======

`Pycopg <http://initd.org/psycopg/>`_ ist ein PostgreSQL-Adapter, der auf der
C-Bibliothek für PostgreSQL `libpq
<https://www.postgresql.org/docs/current/libpq.html>`_ basiert. Er bietet u.a.:

* DB-API-2.0-Kompatibilität
* Multithreading bei Thread Safety
* `Connections pooling <http://initd.org/psycopg/docs/pool.html>`_
  um einen Cache von bestehenden Datenbankverbindungen für Anfragen verwenden
  zu können.
* `Asynchronous
  <http://initd.org/psycopg/docs/advanced.html#asynchronous-support>`_ und
  `Coroutines support
  <http://initd.org/psycopg/docs/advanced.html#support-for-coroutine-libraries>`_
* `Adaptation der Python Typen in SQL
  <http://initd.org/psycopg/docs/usage.html#adaptation-of-python-values-to-sql-types>`_

Installation
------------

Ihr könnt psycopg2 mit Spack installieren, z.B. mit

.. code-block:: console

    $ spack env activate python-374
    $ spack install py-psycopg2 ^python@3.7.4