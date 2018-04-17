# Elasticsearch Cluster

A scalable Elasticsearch cluster

A single volume is shared by master, client and data nodes.

WARN: To avoid vm.max_map_count errors you could set "Update host sysctl" to true. Then param vm.max_map_count will be update to 262144 if it's less in your hosts.
