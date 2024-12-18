# edb_stat_statements

edb_stat_statements is a PostgreSQL extension to support Gel (formerly EdgeDB) query performance statistics.
edb_stat_statements is forked from PostgreSQL `contrib/pg_stat_statements`.

## Installation

```shell
$ make
$ make install
```

Specify `PG_CONFIG` when `pg_config` is not publicly available or installing with a different Postgres installation.
