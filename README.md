# clickhouse

Basic setup clickhouse with sharing and replication
TODO: add replica

## How to deploy

Has to be done using devops account with sudo access.

```
$ ansible-playbook -i hosts deploy.yml -l prod_cluster
```
