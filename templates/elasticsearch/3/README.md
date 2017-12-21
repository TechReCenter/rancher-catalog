# Elasticsearch Cluster

A scalable Elasticsearch cluster work with Host labels

You can setup cluster on hosts list

* cluster=elastic
* role=master
* role=data
* role=client

Disable xpack monitoring with below [config](https://www.elastic.co/guide/en/x-pack/5.2/monitoring-settings.html)

* xpack.monitoring.enabled=false
* xpack.monitoring.collection.interval=-1

WARN: To avoid vm.max_map_count errors you could set "Update host sysctl" to true. Then param vm.max_map_count will be update to 262144 if it's less in your hosts.
