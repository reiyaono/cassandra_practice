## schema
docker-compose run --rm cassandra-load-keyspace cd schema && cqlsh cassandra -f schema.cql

## Enter CQL CLI
docker exec -it cassandra cqlsh

## CQL USAGE
CQL syntax looks like SQL.

```sql
USE test;
SELECT * FROM test_table;
```

## NEXT TASK
- create some cassandra node
- connect to rails 