# Awesome-Managed-Streaming-Data-Pipelines

## Top Managed Streaming Data Pipelines Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Event Processing, Stream Ingestion & Continuous Data Transformation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Managed Streaming Data Pipelines**. These tools ingest, process, transform, and route unbounded event streams from Kafka, CDC sources, webhooks, and message queues — enabling real-time analytics, ETL, feature engineering, and event-driven applications without managing low-level infrastructure.

**Examples** include Salesforce Heroku Data Pipelines, Confluent Cloud, AWS Kinesis, Decodable, Redpanda Cloud, Google Cloud Dataflow, Aiven for Apache Kafka, Estuary Flow, Upstash Kafka, and Bytewax (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom stream processing logic, and transparent data pipelines — ideal for data engineers, platform teams, and developers building data-sovereign streaming infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Heroku Data Pipelines](https://www.heroku.com/)**  
  Managed change data capture (CDC) pipelines that stream Postgres changes to Kafka, enabling real-time data integration on Heroku.

- **[Confluent Cloud](https://www.confluent.io/confluent-cloud/)**  
  Fully managed Apache Kafka service with connectors, ksqlDB, stream processing, and enterprise-grade governance.

- **[AWS Kinesis](https://aws.amazon.com/kinesis/)**  
  Managed real-time streaming service with Data Streams, Data Firehose, and Managed Flink for processing and delivery.

- **[Decodable](https://www.decodable.co/)**  
  Managed stream processing platform built on Apache Flink with SQL-based pipelines and connector ecosystem.

- **[Redpanda Cloud](https://redpanda.com/)**  
  Fully managed Kafka API-compatible streaming platform with built-in tiered storage and no ZooKeeper dependency.

- **[Google Cloud Dataflow](https://cloud.google.com/dataflow)**  
  Fully managed Apache Beam runner for batch and streaming data processing with autoscaling and exactly-once semantics.

- **[Aiven for Apache Kafka](https://aiven.io/kafka)**  
  Managed Kafka service with connectors, schema registry, and integration with Flink and other Aiven services.

- **[Estuary Flow](https://estuary.dev/)**  
  Managed streaming ETL platform with real-time CDC, batch, and streaming pipelines into data warehouses and lakes.

- **[Upstash Kafka](https://upstash.com/kafka)**  
  Serverless Kafka service with pay-per-message pricing and HTTP/REST API access for event streaming.

- **[Bytewax Cloud](https://bytewax.io/)**  
  Managed platform for the Bytewax Python stream processing framework with deployment and scaling controls.

## Open-Source GitHub Projects

- **[Apache Flink](https://github.com/apache/flink)**  
  Leading open-source framework and distributed processing engine for stateful computations over unbounded and bounded data streams. Supports event-time processing, exactly-once semantics, and runs on all common cluster environments [citation:2][citation:12]. Apache 2.0 licensed.

- **[Apache Kafka](https://github.com/apache/kafka)**  
  Distributed event streaming platform for high-performance data pipelines, streaming analytics, and event-driven architecture. Includes Kafka Streams library for stream processing [citation:3][citation:13]. Apache 2.0 licensed.

- **[Apache Beam](https://github.com/apache/beam)**  
  Unified programming model for batch and streaming data processing with SDKs for Java, Python, and Go. Pipelines are portable across runners including Flink, Spark, and Google Cloud Dataflow [citation:4][citation:14]. Apache 2.0 licensed.

- **[Redpanda](https://github.com/redpanda-data/redpanda)**  
  Kafka API-compatible streaming data platform written in C++ with no JVM and no ZooKeeper. Features thread-per-core architecture, Raft per partition, and built-in tiered storage [citation:6][citation:16]. BSL licensed.

- **[Bytewax](https://github.com/bytewax/bytewax)**  
  Python-first stateful stream processing framework with a Rust-based distributed engine. Provides dataflow API with operators like `map`, `filter`, `fold_window`, and `join`, with connectors for Kafka, files, and WebSockets [citation:5][citation:15]. Apache 2.0 licensed.

- **[RisingWave](https://github.com/risingwavelabs/risingwave)**  
  PostgreSQL-compatible streaming database for event-driven applications, real-time ETL, and continuous analytics. Replaces the traditional Debezium + Kafka + Flink + serving DB stack with a single system [citation:7]. Apache 2.0 licensed.

- **[Timeplus Proton](https://github.com/timeplus-io/proton)**  
  Fast unified streaming SQL engine in a single C++ binary with millisecond latency and 100+ GB/s throughput. Supports real-time ETL, telemetry pipelines, and feature engineering with Kafka/ClickHouse integration [citation:10][citation:19]. Apache 2.0 licensed.

- **[Feldera](https://github.com/feldera/feldera)**  
  Incremental computation engine that evaluates arbitrary SQL programs incrementally. Processes millions of events per second on a laptop with full SQL support including joins, aggregates, window functions, and recursive queries [citation:9][citation:18]. Open-source licensed.

- **[Arroyo](https://github.com/ArroyoSystems/arroyo)**  
  Distributed stream processing engine written in Rust. Provides SQL-based stream processing with stateful operations and fault tolerance [citation:8]. Apache 2.0 licensed.

- **[NATS JetStream](https://github.com/nats-io/nats-server)**  
  Cloud-native messaging system with persistent streaming, exactly-once delivery, and key-value store. Lightweight alternative to Kafka for event streaming [citation:1]. Apache 2.0 licensed.

- **[Apache Pulsar](https://github.com/apache/pulsar)**  
  Cloud-native distributed pub-sub messaging and streaming platform with multi-tenancy, geo-replication, and tiered storage [citation:11]. Apache 2.0 licensed.

- **[Benthos (Redpanda Connect)](https://github.com/redpanda-data/benthos)**  
  Stream processor with 200+ connectors for building data pipelines. Declarative configuration with mapping language and support for Kafka, HTTP, and databases [citation:11]. Apache 2.0 licensed.

- **[Quix Streams](https://github.com/quixio/quix-streams)**  
  Python library for Kafka stream processing with pandas-like API for real-time data transformations [citation:11]. Apache 2.0 licensed.

- **[Memphis](https://github.com/memphisdev/memphis)**  
  Real-time data processing platform with built-in schema management, observability, and dead-letter queues [citation:11]. Apache 2.0 licensed.

- **[Apache Storm](https://github.com/apache/storm)**  
  Distributed real-time computation system for processing unbounded streams of data. Classic stream processing framework with spouts and bolts [citation:1]. Apache 2.0 licensed.

- **[Apache Samza](https://github.com/apache/samza)**  
  Distributed stream processing framework built on Kafka with stateful processing and fault tolerance [citation:1]. Apache 2.0 licensed.

### Additional Strong Open-Source Options

- **[Numaflow](https://github.com/numaproj/numaflow)** — Kubernetes-native, language-agnostic platform for scalable event-driven applications [citation:1].
- **[Onyx](https://github.com/onyx-platform/onyx)** — Distributed, masterless, fault-tolerant data processing platform [citation:1].
- **[Proton](https://github.com/timeplus-io/proton)** — Unified streaming and historical data analytics database powered by ClickHouse [citation:1][citation:10].
- **[Siddhi](https://github.com/siddhi-io/siddhi)** — Streaming SQL and complex event processing engine [citation:1].
- **[SQLFlow](https://github.com/sql-machine-learning/sqlflow)** — Stream processing engine that runs DuckDB SQL over Kafka, WebSocket, and webhook streams [citation:1].
- **[Wally](https://github.com/WallarooLabs/wally)** — Distributed stream processing framework formerly named Wallaroo [citation:1].
- **[FastStream](https://github.com/airtai/faststream)** — Asynchronous framework for building event-driven applications with Kafka, RabbitMQ, NATS, Redis, and MQTT [citation:1].
- **[Apache Kafka Streams](https://github.com/apache/kafka)** — Stream processing library included with Apache Kafka [citation:1].
- **Message Queues** — RabbitMQ, ZeroMQ, and Redis Streams for reliable event delivery [citation:11].
- **Schema Registry** — Confluent Schema Registry, Apicurio for managing event schemas.

**Frameworks for building custom systems**: Combine **Apache Kafka** for event transport, **Apache Flink** for stateful processing, **Bytewax** for Python-native pipelines, **RisingWave** or **Feldera** for SQL-based incremental computation, and **Proton** for unified streaming analytics to build a complete self-hosted streaming data pipeline stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Managed streaming data pipelines must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, ISO 27001), and data residency requirements.
- Self-hosted open-source solutions require proper security hardening, high-availability design, and stream processing expertise.

---

**Made for data engineers, platform teams, streaming architects, and developers building real-time data pipeline platforms.**  
Let's make managed streaming data pipelines more open, composable, and developer-friendly.
