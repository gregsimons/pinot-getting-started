# pinot-getting-started

This repository contains the sample schema, table config and kubernetes manifest associated with the Apache developer blog for Exploring OLAP with Apache Pinot.

The kubernetes manifest contains a config map with the cloud event schema and the table config. This is then run in the kubernetes cluster via an Apache Pinot image available on docker hub to create the schema, table and bind to the realtime stream. Kafka topic called cloudevent-topic.