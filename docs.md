## Relationships

Relationships don't require you to specify _explicit endpoints_, because Upsun provides common endpoints by default.

Provide a name for the service (`SERVICE_NAME`) under `services`,
then reuse that name under `relationships`:

```yaml
relationships:
    SERVICE_NAME:
```

Below is an example of using this _default endpoints_ relationships configuration for four services:

```yaml
relationships:
    database:
    database2:
    cache:
    search:
```
