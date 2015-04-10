#Kafka
Installs [kafka](https://kafka.apache.org/)

##Requirements
- kafka_hosts - comma separated list of host:port pairs in the cluster, defaults to 'ansible_fqdn:9092' for a single node 
- zookeeper_hosts - comma separated list of host:port pairs.

##Optional
- kafka_listen_address - defines a specifc address for kafka to listen on, by defaults listens on all interfaces

For a cluster a broker_id must be specified, this is derived from the order of hosts in the `kafka_hosts` variable unless `kafka_id` is set for the host
in which case that is used.

##License
Apache

##Author Information
Tim Kuhlman

Monasca Team email monasca@lists.launchpad.net
