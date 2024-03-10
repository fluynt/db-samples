This repository is a fork of the db-samples northwind databases. Different files have been edited to make them work for our workflow. Below are the commands to load within the fluynt context. This assumes no variable changes, otherwise YMMV.

**mysql and derivitives**

```mysql -u test -h 127.0.0.1 -p fluynt_data < mysql/northwind.sql```

**postgres**

```psql -U test -d fluynt_data -h 127.0.0.1 -f pgsql/northwind.sql```
