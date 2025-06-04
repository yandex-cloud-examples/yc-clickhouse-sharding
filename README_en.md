# Sharding Yandex Managed Service for ClickHouse® tables

There are three possible ways to shard your [Managed Service for ClickHouse®](https://yandex.cloud/en/docs/managed-clickhouse) tables:

* Classic approach, when the distributed table uses all shards in the cluster.
* Regular group-based approach, when some shards are combined into a group.
* Advanced group-based approach, when shards are split into two groups: one group is created for the distributed table, and another one for underlying tables.

See [this tutorial](https://yandex.cloud/en/docs/tutorials/dataplatform/clickhouse-sharding) to learn how to set up the infrastructure for Managed Service for ClickHouse® using Terraform. This repository contains the configuration files you will need: [simple-sharding.tf](simple-sharding.tf), [sharding-with-group.tf](sharding-with-group.tf), and [advanced-sharding-with-groups.tf](advanced-sharding-with-groups.tf).
