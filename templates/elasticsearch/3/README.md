# Elasticsearch Cluster

A scalable Elasticsearch cluster work with Host labels

You can setup cluster on hosts list

* cluster=elastic
* role=master
* role=data
* role=client

WARN: To avoid vm.max_map_count errors you could set "Update host sysctl" to true. Then param vm.max_map_count will be update to 262144 if it's less in your hosts.
