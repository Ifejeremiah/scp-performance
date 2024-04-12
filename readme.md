# Smart Card Redesign Performance


Attached, [view performance](./json/smartcard_uat_dbo_tbl_jobs_01.json),
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
With an average of 39 minutes to process 10,000 records from *new* to *scheduled*.

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
We have generated, [view performance](./json/smartcard_uat_dbo_tbl_jobs_01.json).

