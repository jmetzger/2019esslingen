# Training MariaDB  Galera Cluster - Palette CAD 

## 1. License MaxScale 

```
Version is going to be GPL on Change Data or after 4 years (whatever is earlier) 

https://mariadb.com/projects-using-bsl-11/

Change Date: 2020-01-01 (MaxScale 2.2), 2021-09-01 (MaxScale 2.4.2). For MaxScale 2.4.3 and above, change date is four years from release date.

Before that in BSL 1.1 and 1.0 (from MaxScale 2.0 on), may be used without License Coss
with LESS than 3 Servers 
```

## 2. Good overview of Galera Cluster (How it works) ##

https://severalnines.com/resources/tutorials/galera-cluster-mysql-tutorial

## 3. Performance MaxScale 

Good article on performance MaxScale 

## 4. What does gcomm mean (e.g. in gcomm://) 

Group communication 

## 5. Waht does wsrep mean ? 

Write set Replication 

## 6. Healthiness Indicator of Nodes 

```
# Show status like '%wsrep%'
wsrep_cluster_state: Primary
wsrep_local_state_comment: Synced
wsrep_ready: On
```
