# docker-postgis

```
root@6693969f855e:/# psql -U layers
psql (13.5 (Debian 13.5-1.pgdg110+1))
Type "help" for help.

layers=# select version();
                                                           version                                                           
-----------------------------------------------------------------------------------------------------------------------------
 PostgreSQL 13.5 (Debian 13.5-1.pgdg110+1) on x86_64-pc-linux-gnu, compiled by gcc (Debian 10.2.1-6) 10.2.1 20210110, 64-bit
(1 row)

layers=# select PostGIS_Version();
            postgis_version            
---------------------------------------
 3.1 USE_GEOS=1 USE_PROJ=1 USE_STATS=1
(1 row)

```
