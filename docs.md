## Relationships

Relationships require you to specify _explicit endpoints_:

- a name for the relationship (`REL_NAME`)
- the name of the service (`SERVICE_NAME`)
- the service endpoint (`SERVICE_ENDPOINT`)

Which make up the following configuration:

```yaml
relationships:
    REL_NAME: 'SERVICE_NAME:SERVICE_ENDPOINT'
```

Below is an example of using this _explicit endpoints_ relationships configuration for four services:

```yaml
relationships:
    database: 'mysqldb:db1'
    database2: 'mysqldb:db2'
    cache: 'rediscache:redis'
    search: 'searchserver:elasticsearch'
```
