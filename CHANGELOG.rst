===============================
community.cassandra Release Notes
===============================

.. contents:: Topics

v1.3.0:
=======

Release Summary
---------------

Maintenance release

Minor Changes
-------------

- 230 - Adds basic SSL/TLS support to the cassandra_keyspace, cassandra_role and cassandra_table modules.

v1.2.4:
=======

Release Summary
---------------

Maintenance release

Bug Fixes
---------

- 244 cassandra_repository - Update APT Repository url.

v1.2.3:
=======

Release Summary
---------------

Maintenance release

Bug Fixes
---------

- 239 - cassandra_role - Adds quoting to role name to support special characters in the role name, i.e. my-app-role.

v1.2.2:
=======

Release Summary
---------------

Maintenance release

Bug Fixes
---------

- 214 - cassandra_fullquerylog - Fix typo in documentation.
- 213 - cassandra_cqlsh - Missing handler for `--ssl` option for `cassandra_cqlsh` 