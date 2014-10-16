#Kafka
Installs [kafka](https://kafka.apache.org/)

##Requirements
- zookeeper_hosts - comma separated list of host:port pairs.

Optionally for defining topics, define kafka_topics for example
    kafka_topics:
      metrics: { replicas: 1, partitions: 4 }
      events: { replicas: 1, partitions: 4 }

##License
Apache

##Author Information
Tim Kuhlman
Monasca Team email monasca@lists.launchpad.net
