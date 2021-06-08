# Apache Kafka

Ansible role to install and configure [Apache Kafka 2.7.1](https://downloads.apache.org/kafka/2.7.1/RELEASE_NOTES.html) 

[Apache Kafka] is a distributed event streaming platform using publish-subscribe
topics. Applications and streaming components can produce and consume messages
by subscribing to these topics. Kafka is extremely fast, handling megabytes of
reads and writes per second from thousands of clients. Messages are persisted
and replicated to prevent data loss. Data streams are partitioned and can be
elastically scaled with no downtime.

Repo was cloned from https://github.com/sleighzy/ansible-kafka cause 'other people's bicycles are better than yours'

## TODO:
 - add tests
 - add more supported platforms
 - add zookeeper role to requirements