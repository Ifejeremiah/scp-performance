# Smart Card Redesign Performance


Attached, [view performance](./smartcard_uat_dbo_tbl_jobs_01.json),
is the data generated from smart card process redesign with the following resources;

```yaml
resources:
  limits:
    cpu: '1'
    memory: 2Gi
  requests:
    cpu: 500m
    memory: 500Mi
```

After increasing resources to: 

```yaml
resources:
  limits:
    cpu: '2'
    memory: 4Gi
  requests:
    cpu: '1'
    memory: 1Gi
```
We have this data generated, [view performance](./smartcard_uat_dbo_tbl_jobs_01.json).

