# Dameng JDBC Example

Mycat2 can connect to Dameng through the JDBC datasource provider.

Copy these files into the matching directories under `MYCAT_HOME`:

- `dmDs.datasource.json` -> `datasources/dmDs.datasource.json`
- `dm.cluster.json` -> `clusters/dm.cluster.json`
- `dmtest.schema.json` -> `schemas/dmtest.schema.json`

The datasource URL uses the Dameng JDBC format:

```text
jdbc:dm://127.0.0.1:5236
```

Adjust `user`, `password`, host, port, and `schemaName` for your environment.
