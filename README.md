A fork of the [official PostgreSQL Docker image](https://hub.docker.com/_/postgres/)
with patches to support reactive queries in PostgreSQL.
Based on PostgreSQL 11.1.
See documentation of the official Docker image for details how to run and use this image.

Patches:
* [Temporary materialized views](https://commitfest.postgresql.org/21/1951/)
* [Triggers on materialized views](https://commitfest.postgresql.org/21/1953/)
