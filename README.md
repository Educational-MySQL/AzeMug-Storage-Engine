# AzeMug-Storage-Engine
Educational storage engine from Azerbaijan MySQL User Group. Local community effort to learn and teach database internals concepts.

Compiled MySQL as:

```
cmake -DCMAKE_INSTALL_PREFIX=/opt/mysql56 -DMYSQL_DATADIR=/opt/mysql56/data -DSYSCONFDIR=/opt/mysql56 -DWITH_SSL=system -DMYSQL_TCP_PORT=3307 -DMYSQL_UNIX_ADDR=/opt/mysql56/mysqld.sock -DDEFAULT_CHARSET=utf8 -DDEFAULT_COLLATION=utf8_general_ci -DWITH_DEBUG=1 -DCOMPILATION_COMMENT="AzeMUG MYSQL 5.6" -DOPTIMIZER_TRACE=1 -DWITH_ZLIB=system -DWITH_VALGRIND=1 -DCMAKE_C_FLAGS=-DHAVE_purify -DCMAKE_CXX_FLAGS=-DHAVE_purify -DENABLE_DOWNLOADS=1 -DDOWNLOAD_BOOST=1 -DWITH_BOOST=/opt/mysql56
```
