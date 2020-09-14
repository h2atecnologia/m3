---
title: "Glossary"
date: 2020-04-21T20:45:40-04:00
draft: true
---

1. **Bootstrapping:** Process by which an M3DB node is brought up. Bootstrapping consists of determining the integrity of data that the node has, replay writes from the commit log, and/or stream missing data from its peers.

2. **Cardinality:** The number of unique metrics within the M3DB index. Cardinality increases with the number of unique tag/value combinations that are being emitted.

3. **Datapoint:** A single timestamp/value. Timeseries are composed of multiple datapoints and a series of tag/value pairs.

4. **Labels:** Pairs of descriptive words that give meaning to a metric. Tags and Labels are interchangeable terms.

5. **Metric:** A collection of uniquely identifiable tags.

6. **M3:** Highly scalable, distributed metrics platform that is comprised of a native, distributed time series database, a highly-dynamic and performant aggregation service, a query engine, and other supporting infrastructure.

7. **M3Coordinator:** A service within M3 that coordinates reads and writes between upstream systems, such as Prometheus, and downstream systems, such as M3DB.

8. **M3DB:** Distributed time series database influenced by Gorilla and Cassandra released as open source by Uber Technologies.

9. **M3Query:** A distributed query engine for M3DB. Unlike M3Coordinator, M3Query only provides supports for reads.

10. **Namespace:** Similar to a table in other types of databases, namespaces in M3DB have a unique name and a set of configuration options, such as data retention and block size.

11. **Placement:** Map of the M3DB cluster's shard replicas to nodes. Each M3DB cluster has only one placement. Placement and Topology are interchangeable terms.

12. **Shard:** Effectively the same as a "virtual shard" in Cassandra in that it provides an arbitrary distribution of time series data via a simple hash of the series ID.

13. **Tags:** Pairs of descriptive words that give meaning to a metric. Tags and Labels are interchangeable terms.

14. **Timeseries:** A series of data points tracking a particular metric over time.

15. **Topology:** Map of the M3DB cluster's shard replicas to nodes. Each M3DB cluster has only one placement. Placement and Topology are interchangeable terms.
