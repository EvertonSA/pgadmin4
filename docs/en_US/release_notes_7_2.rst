***********
Version 7.2
***********

Release date: 2023-06-01

This release contains a number of bug fixes and new features since the release of pgAdmin 4 v7.1.

Supported Database Servers
**************************
**PostgreSQL**: 11, 12, 13, 14 and 15

**EDB Advanced Server**: 11, 12, 13, 14 and 15

Bundled PostgreSQL Utilities
****************************
**psql**, **pg_dump**, **pg_dumpall**, **pg_restore**: 15.2


New features
************

  | `Issue #3831 <https://github.com/pgadmin-org/pgadmin4/issues/3831>`_ -  Add Option to only show active connections on Dashboard.


Housekeeping
************


Bug fixes
*********

  | `Issue #5817 <https://github.com/pgadmin-org/pgadmin4/issues/5817>`_ -  Ensure that a new row should be added on top in the User Management dialog.
  | `Issue #6003 <https://github.com/pgadmin-org/pgadmin4/issues/6003>`_ -  Indicate the user if all the server's children nodes are hidden from the preferences setting.
  | `Issue #6026 <https://github.com/pgadmin-org/pgadmin4/issues/6026>`_ -  Tools menu should be toggled for "pause replay of wal" and "resume replay of wal".
  | `Issue #6080 <https://github.com/pgadmin-org/pgadmin4/issues/6080>`_ -  pgAdmin icon not showing on taskbar on Windows 10.
  | `Issue #6127 <https://github.com/pgadmin-org/pgadmin4/issues/6127>`_ -  Fixed an issue where properties were not visible for FTS Parsers, FTS Templates, MViews, and Rules in Catalog objects.
  | `Issue #6147 <https://github.com/pgadmin-org/pgadmin4/issues/6147>`_ -  Heartbeat is getting logged, though no server is connected in pgAdmin.
  | `Issue #6204 <https://github.com/pgadmin-org/pgadmin4/issues/6204>`_ -  Ensure that name can't be empty in edit mode for Primary Key and Index.
  | `Issue #6221 <https://github.com/pgadmin-org/pgadmin4/issues/6221>`_ -  Fix circular reference error for the multirange data types in the query tool.
  | `Issue #6253 <https://github.com/pgadmin-org/pgadmin4/issues/6253>`_ -  Fix an issue in the register server when setting the role, an arbitrary SQL query can be fired.
  | `Issue #6267 <https://github.com/pgadmin-org/pgadmin4/issues/6267>`_ -  Ensure the user is able to log in if the specified OAUTH2_USERNAME_CLAIM is present in the OAuth2 profile.
  | `Issue #6281 <https://github.com/pgadmin-org/pgadmin4/issues/6281>`_ -  VarChar Field Sizes are missing from Query's Grid header.
