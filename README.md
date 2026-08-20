# Awesome Big Data with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 498,094 | 🐛 105 | 📅 2026-08-18

A curated list of awesome big data frameworks, resources and other awesomeness. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) ⭐ 32,663 | 🐛 85 | 📅 2026-07-13, [awesome-python](https://github.com/vinta/awesome-python) ⭐ 315,096 | 🐛 17 | 🌐 Python | 📅 2026-08-16, [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby) ⚠️ Archived, [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://usefulstuff.io/big-data/).

Your contributions are always welcome!

* [Awesome Big Data](#awesome-big-data)
  * [RDBMS](#rdbms)
  * [Frameworks](#frameworks)
  * [Distributed Programming](#distributed-programming)
  * [Distributed Filesystem](#distributed-filesystem)
  * [Distributed Index](#distributed-index)
  * [Document Data Model](#document-data-model)
  * [Key Map Data Model](#key-map-data-model)
  * [Key-value Data Model](#key-value-data-model)
  * [Graph Data Model](#graph-data-model)
  * [Columnar Databases](#columnar-databases)
  * [NewSQL Databases](#newsql-databases)
  * [Time-Series Databases](#time-series-databases)
  * [Lakehouse Table Formats](#lakehouse-table-formats)
  * [SQL-like processing](#sql-like-processing)
  * [Vector Databases](#vector-databases)
  * [Data Ingestion](#data-ingestion)
  * [Data Quality and Observability](#data-quality-and-observability)
  * [Service Programming](#service-programming)
  * [Scheduling](#scheduling)
  * [Machine Learning](#machine-learning)
  * [Benchmarking](#benchmarking)
  * [Security](#security)
  * [System Deployment](#system-deployment)
  * [Applications](#applications)
  * [Search engine and framework](#search-engine-and-framework)
  * [MySQL forks and evolutions](#mysql-forks-and-evolutions)
  * [PostgreSQL forks and evolutions](#postgresql-forks-and-evolutions)
  * [Memcached forks and evolutions](#memcached-forks-and-evolutions)
  * [Embedded Databases](#embedded-databases)
  * [Business Intelligence](#business-intelligence)
  * [Data Visualization](#data-visualization)
  * [Internet of things and sensor data](#internet-of-things-and-sensor-data)
  * [Interesting Readings](#interesting-readings)
  * [Interesting Papers](#interesting-papers)
    * [2015 - 2016](#2015---2016)
    * [2013 - 2014](#2013---2014)
    * [2011 - 2012](#2011---2012)
    * [2001 - 2010](#2001---2010)
  * [Videos](#videos)
  * [Books](#books)
    * [Streaming](#streaming)
    * [Distributed systems](#distributed-systems)
    * [Graph Based approach](#graph-based-approach)
    * [Data Visualization](#data-visualization-1)
* [Other Awesome Lists](#other-awesome-lists)

## RDBMS

* [MySQL](https://www.mysql.com/) The world's most popular open source database.
* [PostgreSQL](https://www.postgresql.org/) The world's most advanced open source database.
* [Oracle Database](http://www.oracle.com/us/corporate/features/database-12c/index.html) - object-relational database management system.
* [Teradata](http://www.teradata.com/products-and-services/teradata-database/) - high-performance MPP data warehouse platform.

## Frameworks

* [Polyaxon](https://github.com/polyaxon/polyaxon) ⭐ 3,721 | 🐛 126 | 🌐 MDX | 📅 2026-08-20 - A platform for reproducible and scalable machine learning and deep learning.
* [Numaflow](https://github.com/numaproj/numaflow) ⭐ 2,825 | 🐛 285 | 🌐 Rust | 📅 2026-08-19 - Kubernetes-native stream processing platform.
* [Bistro](https://github.com/facebook/bistro) ⚠️ Archived - general-purpose data processing engine for both batch and stream analytics. It is based on a novel data model, which represents data via *functions* and processes data via *column operations* as opposed to having only set operations in conventional approaches like MapReduce or SQL.
* [Smooks](https://github.com/smooks/smooks) ⭐ 417 | 🐛 35 | 🌐 Java | 📅 2025-11-24 - An extensible Java framework for building XML and non-XML (CSV, EDI, Java, etc...) streaming applications.
* [Tigon](https://github.com/caskdata/tigon) ⚠️ Archived - High Throughput Real-time Stream Processing Framework.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) - platform for distributed processing and real-time analytics.  Integrates with many of the popular technologies in the Big Data ecosystem (Kafka, HDFS, Spark, etc.)
* [Apache Hadoop](http://hadoop.apache.org/) - framework for distributed processing. Integrates MapReduce (parallel processing), YARN (job scheduling) and HDFS (distributed file system).
* [Pachyderm](http://pachyderm.io/) - Pachyderm is a data storage platform built on Docker and Kubernetes to provide reproducible data processing and analysis.

## Distributed Programming

* [Ray](https://github.com/ray-project/ray) ⭐ 43,568 | 🐛 3,513 | 🌐 Python | 📅 2026-08-20 - A fast and simple framework for building and running distributed applications.
* [Twitter Heron](https://github.com/twitter/heron) ⚠️ Archived - Heron is a realtime, distributed, fault-tolerant stream processing engine from Twitter replacing Storm.
* [Twitter Scalding](https://github.com/twitter/scalding) ⭐ 3,523 | 🐛 317 | 🌐 Scala | 📅 2023-05-28 - Scala library for Map Reduce jobs, built on Cascading.
* [Twitter Summingbird](https://github.com/twitter/summingbird) ⚠️ Archived - Streaming MapReduce with Scalding and Storm, by Twitter.
* [Netflix PigPen](https://github.com/Netflix/PigPen) ⭐ 564 | 🐛 19 | 🌐 Clojure | 📅 2023-04-10 - map-reduce for Clojure which compiles to Apache Pig.
* [AddThis Hydra](https://github.com/addthis/hydra) ⚠️ Archived - distributed data processing and storage system originally developed at AddThis.
* [Skale](https://github.com/skale-me/skale-engine) ⚠️ Archived - High performance distributed data processing in NodeJS.
* [Damballa Parkour](https://github.com/damballa/parkour) ⭐ 255 | 🐛 2 | 🌐 Clojure | 📅 2016-03-23 - MapReduce library for Clojure.
* [Tuktu](https://github.com/UnderstandLingBV/Tuktu) ⭐ 59 | 🐛 6 | 🌐 Scala | 📅 2018-02-15 - Easy-to-use platform for batch and streaming computation, built using Scala, Akka and Play!
* [Datasalt Pangool](https://github.com/datasalt/pangool) ⭐ 57 | 🐛 23 | 🌐 Java | 📅 2022-06-27 - alternative MapReduce paradigm.
* [streamsx.topology](https://github.com/IBMStreams/streamsx.topology) ⭐ 29 | 🐛 3 | 🌐 Java | 📅 2022-07-24 - Libraries to enable building IBM Streams application in Java, Python or Scala.
* [AMPLab SIMR](http://databricks.github.io/simr/) - run Spark on Hadoop MapReduce v1.
* [Apache APEX](https://apex.apache.org/) - a unified, enterprise platform for big data stream and batch processing.
* [Apache Beam](https://beam.apache.org/) - an unified model and set of language-specific SDKs for defining and executing data processing workflows.
* [Apache Crunch](http://crunch.apache.org/) - a simple Java API for tasks like joining and data aggregation that are tedious to implement on plain MapReduce.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) - collection of user-defined functions for Hadoop and Pig developed by LinkedIn.
* [Apache Flink](http://flink.apache.org/) - high-performance runtime, and automatic program optimization.
* [Apache Gearpump](https://gearpump.github.io/gearpump/) - real-time big data streaming engine based on Akka.
* [Apache Gora](http://gora.apache.org/) - framework for in-memory data model and persistence.
* [Apache Hama](http://hama.apache.org/) - BSP (Bulk Synchronous Parallel) computing framework.
* [Apache MapReduce](https://wiki.apache.org/hadoop/MapReduce/) - programming model for processing large data sets with a parallel, distributed algorithm on a cluster.
* [Apache Pig](https://pig.apache.org/) - high level language to express data analysis programs for Hadoop.
* [Apache REEF](http://reef.apache.org/) - retainable evaluator execution framework to simplify and unify the lower layers of big data systems.
* [Apache S4](http://incubator.apache.org/projects/s4.html) - framework for stream processing, implementation of S4.
* [Apache Spark](http://spark.apache.org/) - framework for in-memory cluster computing.
* [Apache Spark Streaming](https://spark.apache.org/docs/latest/streaming-programming-guide.html) - framework for stream processing, part of Spark.
* [Apache Storm](http://storm.apache.org) - framework for stream processing by Twitter also on YARN.
* [Apache Samza](http://samza.apache.org/) - stream processing framework, based on Kafka and YARN.
* [Apache Tez](http://tez.apache.org/) - application framework for executing a complex DAG (directed acyclic graph) of tasks, built on YARN.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) - abstraction over YARN that reduces the complexity of developing distributed applications.
* [Baidu Bigflow](http://bigflow.cloud/en/index.html) - an interface that allows for writing distributed computing programs providing lots of simple, flexible, powerful APIs to easily handle data of any scale.
* [Cascalog](http://cascalog.org/) - data processing and querying library.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) - High Performance, Custom Data Warehouse on Top of MapReduce.
* [Concurrent Cascading](http://www.cascading.org/) - framework for data management/analytics on Hadoop.
* [DataTorrent StrAM](https://www.datatorrent.com/) - real-time engine is designed to enable distributed, asynchronous, real time in-memory big-data computations in as unblocked a way as possible, with minimal overhead and impact on performance.
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) - Hadoop enhancement which removes single point of failure.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) - Map Reduce framework.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) - distributed in-memory datastore.
* [Google Dataflow](https://googledevelopers.blogspot.it/2014/06/cloud-platform-at-google-io-new-big.html) - create data pipelines to help them ingest, transform and analyze data.
* [Google MapReduce](https://research.google.com/archive/mapreduce.html) - map reduce framework.
* [Google MillWheel](https://research.google.com/pubs/pub41378.html) - fault tolerant stream processing framework.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) - platform for distributed processing and real-time analytics.  Provides toolkits for advanced analytics like geospatial, time series, etc. out of the box.
* [JAQL](https://code.google.com/p/jaql/) - declarative programming language for working with structured, semi-structured and unstructured data.
* [Kite](http://kitesdk.org/docs/current/) - is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem.
* [Metamarkets Druid](http://druid.io/) - framework for real-time analysis of large datasets.
* [Nokia Disco](http://discoproject.org/) - MapReduce framework developed by Nokia.
* [Onyx](http://www.onyxplatform.org/) - Distributed computation for the cloud.
* [Pinterest Pinlater](https://medium.com/@Pinterest_Engineering/pinlater-an-asynchronous-job-execution-system-b8664cb8aa7d) - asynchronous job execution system.
* [Pydoop](http://crs4.github.io/pydoop/) - Python MapReduce and HDFS API for Hadoop.
* [Rackerlabs Blueflood](http://blueflood.io/) - multi-tenant distributed metric processing system
* [Stratosphere](http://stratosphere.eu/) - general purpose cluster computing framework.
* [Streamdrill](https://streamdrill.com/) - useful for counting activities of event streams over different time windows and finding the most active one.
* [Twitter TSAR](https://blog.twitter.com/engineering/en_us/a/2014/tsar-a-timeseries-aggregator.html) - TimeSeries AggregatoR by Twitter.
* [Wallaroo](http://www.wallaroolabs.com/community) - The ultrafast and elastic data processing engine. Big or fast data - no fuss, no Java needed.

## Distributed Filesystem

* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,346 | 🐛 200 | 🌐 Go | 📅 2026-08-20 - distributed POSIX file system built on object storage.
* [Baidu File System](https://github.com/baidu/bfs) ⭐ 2,847 | 🐛 119 | 🌐 C++ | 📅 2018-12-03 - distributed filesystem.
* [Ambry](https://github.com/linkedin/ambry) ⭐ 1,785 | 🐛 139 | 🌐 Java | 📅 2026-08-20 - a distributed object store that supports storage of trillion of small immutable objects as well as billions of large objects.
* [Seaweed-FS](https://github.com/chrislusf/seaweedfs) ⭐ 36 | 🐛 1 | 🌐 Go | 📅 2026-07-21 - simple and highly scalable distributed file system.
* [Apache HDFS](http://hadoop.apache.org/) - a way to store large files across multiple machines.
* [Apache Kudu](http://kudu.apache.org/) - Hadoop's storage layer to enable fast analytics on fast data.
* [BeeGFS](https://www.beegfs.io/content/) - formerly FhGFS, parallel distributed file system.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) - software storage platform designed.
* [Disco DDFS](http://disco.readthedocs.org/en/latest/howto/ddfs.html) - distributed filesystem.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) - object storage system.
* [Google GFS](http://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) - distributed filesystem.
* [Google Megastore](https://research.google.com/pubs/pub36971.html) - scalable, highly available storage.
* [GridGain](https://www.gridgain.com/) - GGFS, Hadoop compliant in-memory file system.
* [Lustre file system](http://wiki.lustre.org/) - high-performance distributed filesystem.
* [Microsoft Azure Data Lake Store](https://hadoop.apache.org/docs/current/hadoop-azure-datalake/index.html) - HDFS-compatible storage in Azure cloud
* [Quantcast File System QFS](https://www.quantcast.com/about-us/quantcast-file-system/) - open-source distributed file system.
* [Red Hat GlusterFS](http://gluster.org/) - scale-out network-attached storage file system.
* [Alluxio](http://www.alluxio.org/) - reliable file sharing at memory speed across cluster frameworks.
* [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) - decentralized cloud storage system.

## Distributed Index

* [Pilosa](https://github.com/pilosa/pilosa) ⚠️ Archived Open source distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.

## Document Data Model

* [Actian Versant](https://www.actian.com/data-management/ingres-sql-rdbms/) - commercial object-oriented database management systems .
* [Crate Data](https://crate.io/) - is an open source massively scalable data store. It requires zero administration.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo) - Facebook’s Paxos-like NoSQL database.
* [jumboDB](http://comsysto.github.io/jumbodb/) - document oriented datastore over Hadoop.
* [LinkedIn Espresso](https://engineering.linkedin.com/data) - horizontally scalable document-oriented NoSQL data store.
* [MarkLogic](http://www.marklogic.com/) - Schema-agnostic Enterprise NoSQL database technology.
* [Microsoft Azure DocumentDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - NoSQL cloud database service with protocol support for MongoDB
* [MongoDB](https://www.mongodb.com/) - Document-oriented database system.
* [RavenDB](https://ravendb.net/) - A transactional, open-source Document Database.
* [RethinkDB](https://rethinkdb.com/) - document database that supports queries like table joins and group by.

## Key Map Data Model

**Note**: There is some term confusion in the industry, and two different things are called "Columnar Databases". Some, listed here, are distributed, persistent databases built around the "key-map" data model: all data has a (possibly composite) key, with which a map of key-value pairs is associated. In some systems, multiple such value maps can be associated with a key, and these maps are referred to as "column families" (with value map keys being referred to as "columns").

Another group of technologies that can also be called "columnar databases" is distinguished by how it stores data, on disk or in memory -- rather than storing data the traditional way, where all column values for a given key are stored next to each other, "row by row", these systems store all *column* values next to each other. So more work is needed to get all columns for a given key, but less work is needed to get all values for a given column.

The former group is referred to as "key map data model" here. The line between these and the [Key-value Data Model](#key-value-data-model) stores is fairly blurry.

The latter, being more about the storage format than about the data model, is listed under [Columnar Databases](#columnar-databases).

You can read more about this distinction on Prof. Daniel Abadi's blog: [Distinguishing two major types of Column Stores](http://dbmsmusings.blogspot.com/2010/03/distinguishing-two-major-types-of_29.html).

* [Baidu Tera](https://github.com/baidu/tera) ⭐ 1,902 | 🐛 172 | 🌐 C++ | 📅 2024-06-05 - an Internet-scale database, inspired by BigTable.
* [InfiniDB](https://github.com/infinidb/infinidb/) ⭐ 248 | 🐛 1 | 🌐 C++ | 📅 2017-10-14 - is accessed through a MySQL interface and use massive parallel processing to parallelize queries.
* [Tephra](https://github.com/caskdata/tephra) ⚠️ Archived - Transactions for HBase.
* [Apache Accumulo](http://accumulo.apache.org/) - distributed key/value store, built on Hadoop.
* [Apache Cassandra](http://cassandra.apache.org/) - column-oriented distributed datastore, inspired by BigTable.
* [Apache HBase](http://hbase.apache.org/) - column-oriented distributed datastore, inspired by BigTable.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) - evolution of HBase made by Facebook.
* [Google BigTable](http://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) - column-oriented distributed datastore.
* [Google Cloud Datastore](https://cloud.google.com/datastore/docs/concepts/overview) - is a fully managed, schemaless database for storing non-relational data over BigTable.
* [Hypertable](http://www.hypertable.org/) - column-oriented distributed datastore, inspired by BigTable.
* [Twitter Manhattan](https://blog.twitter.com/engineering/en_us/a/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale.html) - real-time, multi-tenant distributed database for Twitter scale.
* [ScyllaDB](http://www.scylladb.com/) - column-oriented distributed datastore written in C++, totally compatible with Apache Cassandra.

## Key-value Data Model

* [TiKV](https://github.com/pingcap/tikv) ⭐ 16,808 | 🐛 1,804 | 🌐 Rust | 📅 2026-08-20 - a distributed key-value database powered by Rust and inspired by Google Spanner and HBase.
* [Bolt](https://github.com/boltdb/bolt) ⚠️ Archived - an embedded key-value database for Go.
* [Tile38](https://github.com/tidwall/tile38) ⭐ 9,715 | 🐛 163 | 🌐 Go | 📅 2026-08-07 - a geolocation data store, spatial index, and realtime geofence, supporting a variety of object types including latitude/longitude points, bounding boxes, XYZ tiles, Geohashes, and GeoJSON
* [BuntDB](https://github.com/tidwall/buntdb) ⭐ 4,863 | 🐛 32 | 🌐 Go | 📅 2026-05-19 - a fast, embeddable, in-memory key/value database for Go with custom indexing and geospatial support.
* [Riak](https://github.com/basho/riak) ⭐ 4,028 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 - a decentralized datastore.
* [Tarantool](https://github.com/tarantool/tarantool) ⭐ 3,663 | 🐛 1,694 | 🌐 Lua | 📅 2026-08-20 - an efficient NoSQL database and a Lua application server.
* [GridDB](https://github.com/griddb/griddb_nosql) ⭐ 2,476 | 🐛 51 | 🌐 C++ | 📅 2026-03-19 - suitable for sensor data stored in a timeseries.
* [SummitDB](https://github.com/tidwall/summitdb) ⚠️ Archived - an in-memory, NoSQL key/value database, with disk persistence and using the Raft consensus algorithm.
* [HyperDex](https://github.com/rescrv/HyperDex) ⭐ 1,405 | 🐛 37 | 🌐 C++ | 📅 2024-05-21 - a scalable, next generation key-value and document store with a wide array of features, including consistency, fault tolerance and high performance.
* [GhostDB](https://github.com/jakekgrog/GhostDB) ⭐ 752 | 🐛 12 | 🌐 Go | 📅 2021-03-10 - a distributed, in-memory, general purpose key-value data store that delivers microsecond performance at any scale.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) ⭐ 559 | 🐛 4 | 🌐 Java | 📅 2014-06-27 - Distributed database specialized in exporting data from Hadoop.
* [Edis](https://github.com/cbd/edis) ⭐ 518 | 🐛 13 | 🌐 Erlang | 📅 2015-09-14 - is a protocol-compatible Server replacement for Redis.
* [Storehaus](https://github.com/twitter/storehaus) ⭐ 465 | 🐛 78 | 🌐 Scala | 📅 2020-07-17 - library to work with asynchronous key value stores, by Twitter.
* [Graviton](https://github.com/deroproject/graviton) ⭐ 424 | 🐛 4 | 🌐 Go | 📅 2022-01-30 - a simple, fast, versioned, authenticated, embeddable key-value store database in pure Go(lang).
* [TreodeDB](https://github.com/Treode/store) ⭐ 177 | 🐛 0 | 🌐 Scala | 📅 2015-10-31 - key-value store that's replicated and sharded and provides atomic multirow writes.
* [BTDB](https://github.com/Bobris/BTDB) ⭐ 144 | 🐛 3 | 🌐 C# | 📅 2026-08-08 - Key Value Database in .Net with Object DB Layer, RPC, dynamic IL and much more
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) ⭐ 26 | 🐛 0 | 🌐 PHP | 📅 2012-09-05 - is a simple persistent data store with very low latency and high throughput.
* [Aerospike](http://www.aerospike.com/) - NoSQL flash-optimized, in-memory. Open source and "Server code in 'C' (not Java or Erlang) precisely tuned to avoid context switching and memory copies."
* [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - distributed key/value store, implementation of Dynamo paper.
* [Badger](https://open.dgraph.io/post/badger/) - a fast, simple, efficient, and persistent key-value store written natively in Go.
* [EventStore](https://geteventstore.com/) - distributed time series database.
* [Ignite](https://ignite.apache.org/index.html) - is an in-memory key-value data store providing full SQL-compliant data access that can optionally be backed by disk storage.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) - distributed key/value storage system.
* [Oracle NoSQL Database](http://www.oracle.com/technetwork/database/database-technologies/nosqldb/overview/index.html) - distributed key-value database by Oracle Corporation.
* [Redis](https://redis.io/) - in memory key value datastore.

## Graph Data Model

* [DGraph](https://github.com/dgraph-io/dgraph) ⭐ 21,779 | 🐛 96 | 🌐 Go | 📅 2026-08-20 - A scalable, distributed, low latency, high throughput graph database aimed at providing Google production level scale and throughput, with low enough latency to be serving real time user queries, over terabytes of structured data.
* [Google Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,060 | 🐛 93 | 🌐 Go | 📅 2026-08-17 - open-source graph database.
* [Microsoft Graph Engine](https://github.com/Microsoft/GraphEngine) ⭐ 2,262 | 🐛 47 | 🌐 C# | 📅 2024-10-08 - a distributed in-memory data processing engine, underpinned by a strongly-typed in-memory key-value store and a general distributed computation engine.
* [Gremlin](https://github.com/tinkerpop/gremlin) ⭐ 1,951 | 🐛 21 | 🌐 Java | 📅 2021-08-16 - graph traversal Language.
* [GCHQ Gaffer](https://github.com/gchq/Gaffer) ⚠️ Archived - Gaffer by GCHQ is a framework that makes it easy to store large-scale graphs in which the nodes and edges have statistics.
* [AgensGraph](https://github.com/bitnine-oss/agensgraph) ⭐ 1,507 | 🐛 137 | 🌐 C | 📅 2026-08-20 - transactional graph database based on PostgreSQL.
* [EliasDB](https://github.com/krotik/eliasdb) ⭐ 1,035 | 🐛 14 | 🌐 Go | 📅 2022-08-14 - a lightweight graph based database that does not require any third-party libraries.
* [Phoebus](https://github.com/xslogic/phoebus) ⭐ 384 | 🐛 0 | 🌐 Erlang | 📅 2012-01-15 - framework for large scale graph processing.
* [Actionbase](https://github.com/kakao/actionbase) ⭐ 225 | 🐛 44 | 🌐 Kotlin | 📅 2026-08-20 - a database for user interactions (likes, views, follows) with precomputed reads, supports HBase.
* [Infovore](https://github.com/paulhoule/infovore) ⭐ 148 | 🐛 50 | 🌐 Java | 📅 2021-11-15 - RDF-centric Map/Reduce framework.
* [ArcadeDB](https://arcadedb.com/) - multi-model database with graph, document, key-value, time-series and vector support.
* [Apache Spark Bagel](http://spark.apache.org/docs/0.7.3/bagel-programming-guide.html) - implementation of Pregel, part of Spark.
* [ArangoDB](https://www.arangodb.com/) - multi model distributed database.
* [Facebook TAO](https://engineering.fb.com/2013/06/25/core-infra/tao-the-power-of-the-graph/) - TAO is the distributed data store that is widely used at Facebook to store and serve the social graph.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) - graph processing framework.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) - resilient Distributed Graph System on Spark.
* [JanusGraph](http://janusgraph.org) - open-source, distributed graph database
  with multiple options for storage backends (Bigtable, HBase, Cassandra, etc.)
  and indexing backends (Elasticsearch, Solr, Lucene).
* [Nebula Graph](https://www.nebula-graph.io/) - distributed graph database for large-scale graphs with low-latency queries.
* [Neo4j](https://neo4j.com/) - graph database written entirely in Java.
* [OrientDB](http://orientdb.com/) - document and graph database.
* [Titan](http://thinkaurelius.github.io/titan/) - distributed graph database, built over Cassandra.

## Columnar Databases

**Note** please read the note on [Key-Map Data Model](#key-map-data-model) section.

* [LocustDB](https://github.com/cswinter/LocustDB) ⭐ 1,648 | 🐛 14 | 🌐 Rust | 📅 2026-04-23 - an experimental analytics database aiming to set a new standard for query performance on commodity hardware.
* [IndexR](https://github.com/shunfei/indexr) ⭐ 447 | 🐛 10 | 🌐 Java | 📅 2022-11-16 - an open-source columnar storage format for fast & realtime analytic with big data.
* [Columnar Storage](http://the-paper-trail.org/blog/columnar-storage/) - an explanation of what columnar storage is and when you might want it.
* [Actian Vector](http://www.actian.com/) - column-oriented analytic database.
* [ClickHouse](https://clickhouse.com/) - an open-source column-oriented database management system that allows generating analytical data reports in real time.
* [EventQL](http://eventql.io/) - a distributed, column-oriented database built for large-scale event collection and analytics.
* [MonetDB](https://www.monetdb.org/) - column store database.
* [Parquet](http://parquet.apache.org/) - columnar storage format for Hadoop.
* [Pivotal Greenplum](https://pivotal.io/pivotal-greenplum) - purpose-built, dedicated analytic data warehouse that offers a columnar engine as well as a traditional row-based one.
* [Vertica](https://www.vertica.com/) - is designed to manage large, fast-growing volumes of data and provide very fast query performance when used for data warehouses.
* [SQream DB](http://sqream.com/) - A GPU powered big data database, designed for analytics and data warehousing, with ANSI-92 compliant SQL, suitable for data sets from 10TB to 1PB.
* [Google BigQuery](https://cloud.google.com/bigquery/what-is-bigquery) - Google's cloud offering backed by their pioneering work on Dremel.
* [Amazon Redshift](https://aws.amazon.com/redshift/) - Amazon's cloud offering, also based on a columnar datastore backend.

## NewSQL Databases

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,454 | 🐛 6,826 | 🌐 Go | 📅 2026-08-20 - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [Cockroach](https://github.com/cockroachdb/cockroach) ⭐ 32,404 | 🐛 8,209 | 🌐 Go | 📅 2026-08-07 - Scalable, Geo-Replicated, Transactional Datastore.
* [yugabyteDB](https://github.com/YugaByte/yugabyte-db) ⭐ 10,484 | 🐛 8,285 | 🌐 C | 📅 2026-08-20 - open source, high-performance, distributed SQL database compatible with PostgreSQL.
* [ActorDB](https://github.com/biokoda/actordb) ⭐ 1,888 | 🐛 32 | 🌐 Erlang | 📅 2022-11-10 - a distributed SQL database with the scalability of a KV store, while keeping the query capabilities of a relational database.
* [Comdb2](https://github.com/bloomberg/comdb2) ⭐ 1,526 | 🐛 294 | 🌐 C | 📅 2026-08-20 - a clustered RDBMS built on optimistic concurrency control techniques.
* [BayesDB](https://github.com/probcomp/BayesDB) ⭐ 889 | 🐛 0 | 📅 2015-09-24 - statistic oriented SQL database.
* [KarelDB](https://github.com/rayokota/kareldb) ⭐ 389 | 🐛 12 | 🌐 Java | 📅 2025-10-15 - a relational database backed by Apache Kafka.
* [Haeinsa](https://github.com/VCNC/haeinsa) ⭐ 160 | 🐛 19 | 🌐 Java | 📅 2017-02-28 - linearly scalable multi-row, multi-table transaction library for HBase based on Percolator.
* [Actian Ingres](http://www.actian.com/products/operational-databases/) - commercially supported, open-source SQL relational database management system.
* [Amazon RedShift](http://aws.amazon.com/redshift/) - data warehouse service, based on PostgreSQL.
* [Bedrock](http://bedrockdb.com/) - a simple, modular, networked and distributed transaction layer built atop SQLite.
* [CitusDB](https://www.citusdata.com/) - scales out PostgreSQL through sharding and replication.
* [Datomic](http://www.datomic.com/) - distributed database designed to enable scalable, flexible and intelligent applications.
* [FoundationDB](https://foundationdb.com/) - distributed database, inspired by F1.
* [Google F1](https://research.google.com/pubs/pub41344.html) - distributed SQL database built on Spanner.
* [Google Spanner](https://research.google.com/archive/spanner.html) - globally distributed semi-relational database.
* [H-Store](http://hstore.cs.brown.edu/) - is an experimental main-memory, parallel database management system that is optimized for on-line transaction processing (OLTP) applications.
* [HandlerSocket](https://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) - NoSQL plugin for MySQL/MariaDB.
* [InfiniSQL](http://www.infinisql.org/) - infinity scalable RDBMS.
* [Map-D](https://www.mapd.com/) - GPU in-memory database, big data analysis and visualization platform.
* [MemSQL](http://www.memsql.com/) - in memory SQL database witho optimized columnar storage on flash.
* [NuoDB](http://www.nuodb.com/) - SQL/ACID compliant distributed database.
* [Oracle TimesTen in-Memory Database](http://www.oracle.com/technetwork/database/database-technologies/timesten/overview/index.html) - in-memory, relational database management system with persistence and recoverability.
* [Pivotal GemFire XD](https://gemfire.docs.pivotal.io/93/gemfire/getting_started/gemfire_overview.html) - Low-latency, in-memory, distributed SQL data store. Provides SQL interface to in-memory table data, persistable in HDFS.
* [SAP HANA](https://hana.sap.com/abouthana.html) - is an in-memory, column-oriented, relational database management system.
* [SenseiDB](http://senseidb.github.io/sensei/) - distributed, realtime, semi-structured database.
* [Sky](http://skydb.io/) - database used for flexible, high performance analysis of behavioral data.
* [SymmetricDS](http://www.symmetricds.org/) - open source software for both file and database synchronization.
* [VoltDB](https://www.voltdb.com/) - claims to be fastest in-memory database.

## Time-Series Databases

* [TDengine](https://github.com/taosdata/TDengine/) ⭐ 25,068 | 🐛 447 | 🌐 C | 📅 2026-08-16 - open-source time-series database with high-performance ingestion, SQL support, and IoT-oriented storage.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,574 | 🐛 769 | 🌐 Go | 📅 2026-08-20 - fast, scalable and resource-effective open-source TSDB compatible with Prometheus. Single-node and cluster versions included
* [Thanos](https://github.com/improbable-eng/thanos) ⭐ 14,180 | 🐛 879 | 🌐 Go | 📅 2026-08-17 - Thanos is a set of components to create a highly available metric system with unlimited storage capacity using multiple (existing) Prometheus deployments.
* [Druid](https://github.com/druid-io/druid/) ⭐ 14,044 | 🐛 805 | 🌐 Java | 📅 2026-08-20 Column oriented distributed data store ideal for powering interactive applications
* [Beringei](https://github.com/facebookincubator/beringei) ⚠️ Archived - Facebook's in-memory time-series database.
* [Kairosdb](https://github.com/kairosdb/kairosdb) ⭐ 1,762 | 🐛 141 | 🌐 Java | 📅 2026-03-05 - similar to OpenTSDB but allows for Cassandra.
* [Akumuli](https://github.com/akumuli/Akumuli) ⚠️ Archived Akumuli is a numeric time-series database. It can be used to capture, store and process time-series data in real-time. The word "akumuli" can be translated from esperanto as "accumulate".
* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) ⭐ 692 | 🐛 28 | 🌐 Erlang | 📅 2019-02-11 Fast distributed metrics database
* [Blueflood](https://github.com/rackerlabs/blueflood) ⭐ 598 | 🐛 54 | 🌐 Java | 📅 2024-08-19 A distributed system designed to ingest and process time series data
* [SiriDB](https://github.com/transceptor-technology/siridb-server) ⭐ 514 | 🐛 4 | 🌐 C | 📅 2026-07-27 Highly-scalable, robust and fast, open source time series database with cluster functionality.
* [Timely](https://github.com/NationalSecurityAgency/timely) ⭐ 396 | 🐛 20 | 🌐 Java | 📅 2026-05-13 Timely is a time series database application that provides secure access to time series data based on Accumulo and Grafana.
* [Axibase Time Series Database](http://axibase.com/products/axibase-time-series-database/) - Integrated time series database on top of HBase with built-in visualization, rule-engine and SQL support.
* [Chronix](http://chronix.io/) - a time series storage built to store time series highly compressed and for fast access times.
* [Cube](http://square.github.io/cube/) - uses MongoDB to store time series data.
* [Heroic](https://spotify.github.io/heroic/#!/index) - is a scalable time series database based on Cassandra and Elasticsearch.
* [InfluxDB](https://www.influxdata.com/) - a time series database with optimised IO and queries, supports pgsql and influx wire protocols.
* [QuestDB](https://questdb.io/) - high-performance, open-source SQL database for applications in financial services, IoT, machine learning, DevOps and observability.
* [IronDB](https://www.circonus.com/irondb/) - scalable, general-purpose time series database.
* [M3DB](https://m3db.io/) - a distributed time series database that can be used for storing realtime metrics at long retention.
* [Newts](https://opennms.github.io/newts/) - a time series database based on Apache Cassandra.
* [OpenTSDB](http://opentsdb.net) - distributed time series database on top of HBase.
* [Prometheus](https://prometheus.io/) - a time series database and service monitoring system.
* [TrailDB](http://traildb.io/) - an efficient tool for storing and querying series of events.
* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS is the only enterprise-grade NoSQL time series database optimized specifically for IoT and Time Series data.
* [Rhombus](https://github.com/Pardot/Rhombus) A time-series object store for Cassandra that handles all the complexity of building wide row indexes.

## Lakehouse Table Formats

* [Apache Hudi](https://hudi.apache.org/) - open data lakehouse platform and table format for high-throughput incremental data pipelines.
* [Apache Iceberg](https://iceberg.apache.org/) - open table format for huge analytic datasets with schema evolution, hidden partitioning, and time travel.
* [Apache Paimon](https://paimon.apache.org/) - lake format for building real-time lakehouse architectures with Flink and Spark.
* [Apache XTable](https://xtable.apache.org/) - incubating Apache project for interoperability across lakehouse table formats.
* [Delta Lake](https://delta.io/) - open-source storage framework for building lakehouse architectures on data lakes.

## SQL-like processing

* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) ⭐ 43,842 | 🐛 483 | 🌐 Scala | 📅 2026-08-20 - is a Query Optimization Framework for Spark and Shark.
* [Materialize](https://github.com/materializeinc/materialize) ⭐ 6,357 | 🐛 719 | 🌐 Rust | 📅 2026-08-20 - is a streaming database for real-time applications using SQL for queries and supporting a large fraction of PostgreSQL.
* [chDB](https://github.com/chdb-io/chdb) ⭐ 2,872 | 🐛 39 | 🌐 Python | 📅 2026-08-20 - in-process OLAP SQL engine powered by ClickHouse, callable from Python with native pandas/Arrow DataFrame interop.
* [Actian SQL for Hadoop](http://www.actian.com/analytic-database/vectorh-sql-hadoop) - high performance interactive SQL access to all Hadoop data.
* [Apache Doris](https://doris.apache.org/) - real-time analytical database for high-concurrency SQL analytics, search, and warehousing.
* [Apache Drill](http://drill.apache.org/) - framework for interactive analysis, inspired by Dremel.
* [Apache HCatalog](https://cwiki.apache.org/confluence/display/Hive/HCatalog) - table and storage management layer for Hadoop.
* [Apache Hive](http://hive.apache.org/) - SQL-like data warehouse system for Hadoop.
* [Apache Calcite](http://calcite.apache.org/) - framework that allows efficient translation of queries involving heterogeneous and federated data.
* [Apache Phoenix](http://phoenix.apache.org/index.html) - SQL skin over HBase.
* [Aster Database](http://www.teradata.com/products-and-services/Teradata-Aster/teradata-aster-database) - SQL-like analytic processing for MapReduce.
* [Cloudera Impala](https://www.cloudera.com/products/apache-hadoop/impala.html) - framework for interactive analysis, Inspired by Dremel.
* [Concurrent Lingual](http://www.cascading.org/projects/lingual/) - SQL-like query language for Cascading.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) - full SQL query engine for big datasets.
* [Dremio](https://www.dremio.com/) - an open-source, SQL-like Data-as-a-Service Platform based on Apache Arrow.
* [DuckDB](https://duckdb.org/) - in-process analytical SQL database for local analytics over files, data lakes, and data frames.
* [Facebook PrestoDB](https://prestodb.io/) - distributed SQL query engine.
* [Google BigQuery](https://research.google.com/pubs/pub36632.html) - framework for interactive analysis, implementation of Dremel.
* [Invantive SQL](https://documentation.invantive.com/2017R2/invantive-sql-grammar/invantive-sql-grammar-17.30.html) - SQL engine for online and on-premise use with integrated local data replication and 70+ connectors.
* [PipelineDB](https://www.pipelinedb.com/) - an open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables.
* [Pivotal HDB](https://pivotal.io/pivotal-hdb) - SQL-like data warehouse system for Hadoop.
* [rawquery](https://rawquery.dev/) - managed lakehouse query service using DuckDB over Apache Iceberg tables on object storage.
* [RainstorDB](http://rainstor.com/products/rainstor-database/) - database for storing petabyte-scale volumes of structured and semi-structured data.
* [SparkSQL](https://databricks.com/blog/2014/03/26/spark-sql-manipulating-structured-data-using-spark-2.html) - Manipulating Structured Data Using Spark.
* [Splice Machine](https://www.splicemachine.com/) - a full-featured SQL-on-Hadoop RDBMS with ACID transactions.
* [StarRocks](https://www.starrocks.io/) - high-performance MPP SQL engine for real-time analytics and lakehouse queries.
* [Stinger](https://hortonworks.com/innovation/stinger/) - interactive query for Hive.
* [Tajo](http://tajo.apache.org/) - distributed data warehouse system on Hadoop.
* [Trafodion](https://wiki.trafodion.org/wiki/index.php/Main_Page) - enterprise-class SQL-on-HBase solution targeting big data transactional or operational workloads.
* [Trino](https://trino.io/) - distributed SQL query engine for querying large datasets across heterogeneous data sources.

## Vector Databases

* [Milvus](https://github.com/milvus-io/milvus) ⭐ 45,710 | 🐛 1,318 | 🌐 Go | 📅 2026-08-20 - open-source vector database for scalable similarity search.
* [Zvec](https://github.com/alibaba/zvec) ⭐ 15,479 | 🐛 59 | 🌐 C++ | 📅 2026-08-20 - open-source, in-process vector database for dense, sparse, and hybrid similarity search.
* [Infinity](https://github.com/infiniflow/infinity) ⭐ 4,676 | 🐛 64 | 🌐 C++ | 📅 2026-08-17 - AI-native database for hybrid vector, sparse vector, tensor, full-text, and structured search.
* [Chroma](https://www.trychroma.com/) - open-source embedding database for AI applications.
* [LanceDB](https://www.lancedb.com/) - open-source embedded vector database built on the Lance columnar format.
* [Qdrant](https://qdrant.tech/) - vector database and similarity search engine with REST, gRPC, and client SDKs.
* [Weaviate](https://weaviate.io/) - open-source vector database for semantic search with structured filtering.

## Data Ingestion

* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,310 | 🐛 1,730 | 🌐 Java | 📅 2026-08-20 - a distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,475 | 🐛 50 | 🌐 Go | 📅 2026-08-20 - an open source customer data infrastructure (segment, mParticle  alternative) written in go.
* [Facebook Scribe](https://github.com/facebookarchive/scribe) ⚠️ Archived - streamed log data aggregator.
* [ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,850 | 🐛 15 | 🌐 Go | 📅 2026-08-19 - CLI tool for copying data between sources and destinations.
* [Heka](https://github.com/mozilla-services/heka) ⚠️ Archived - open source stream processing software system.
* [Linkedin Gobblin](https://github.com/linkedin/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-07-31 - linkedin's universal data ingestion framework.
* [Pinterest Secor](https://github.com/pinterest/secor) ⭐ 1,856 | 🐛 269 | 🌐 Java | 📅 2026-03-10 - is a service implementing Kafka log persistance.
* [Bruin](https://github.com/bruin-data/bruin) ⭐ 1,671 | 🐛 32 | 🌐 Go | 📅 2026-08-20 - end-to-end data pipeline tool combining ingestion, transformations, and data quality checks.
* [Zilla](https://github.com/aklivity/zilla) ⭐ 1,644 | 🐛 220 | 🌐 Java | 📅 2026-08-20 - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.
* [Duckle](https://github.com/slothflowlabs/duckle) ⭐ 1,172 | 🐛 60 | 🌐 Rust | 📅 2026-08-20 - open-source visual ETL/ELT platform built on DuckDB with connectors, data quality checks, and lineage.
* [Netflix Suro](https://github.com/Netflix/suro) ⚠️ Archived - log agregattor like Storm and Samza based on Chukwa.
* [Gazette](https://github.com/gazette/core) ⭐ 795 | 🐛 21 | 🌐 Go | 📅 2026-07-25 - Distributed streaming infrastructure built on cloud storage which makes it easy to mix and match batch and streaming paradigms.
* [Skizze](https://github.com/skizzehq/skizze) ⭐ 773 | 🐛 10 | 🌐 Go | 📅 2016-05-10 - sketch data store to deal with all problems around counting and sketching using probabilistic data-structures.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) ⚠️ Archived - log aggregator and dashboard.
* [HIHO](https://github.com/sonalgoyal/hiho) ⭐ 92 | 🐛 5 | 🌐 Java | 📅 2013-04-11 - framework for connecting disparate data sources with Hadoop.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) ⭐ 22 | 🐛 4 | 🌐 Java | 📅 2014-03-07 - utility package for compressing sorted integer arrays.
* [redpanda](https://vectorized.io/redpanda) - A Kafka® replacement for mission critical systems; 10x faster. Written in C++.
* [Airbyte](https://airbyte.com/) - open-source data movement platform for ELT pipelines and connector-based replication.
* [Amazon Kinesis](https://aws.amazon.com/kinesis/) - real-time processing of streaming data at massive scale.
* [Amazon Web Services Glue](https://aws.amazon.com/glue/) -  serverless fully managed extract, transform, and load (ETL) service
* [Apache Chukwa](http://chukwa.apache.org/) - data collection system.
* [Apache Flume](http://flume.apache.org/) - service to manage large amount of log data.
* [Apache Kafka](http://kafka.apache.org/) - distributed publish-subscribe messaging system.
* [Apache NiFi](https://nifi.apache.org/) - Apache NiFi is an integrated data logistics platform for automating the movement of data between disparate systems.
* [Apache SeaTunnel](https://seatunnel.apache.org/) - high-performance, distributed data integration platform for batch and streaming synchronization.
* [Apache Sqoop](http://sqoop.apache.org/) - tool to transfer data between Hadoop and a structured datastore.
* [Census](https://getcensus.com/) - A reverse ETL product that let you sync data from your data warehouse to SaaS Applications. No engineering favors required—just SQL.
* [DataRaven](https://dataraven.io/) - managed cloud object storage transfers for data ingestion workflows.
* [DBConvert Streams](https://streams.dbconvert.com/cdc-replication/) - self-hosted CDC replication and database migration tool.
* [Debezium](https://debezium.io/) - open-source distributed platform for change data capture.
* [Embulk](http://www.embulk.org) - open-source bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
* [Estuary](https://estuary.dev) - SaaS platform based on Gazette with plug-and-play connectors.
* [Flink CDC](https://nightlies.apache.org/flink/flink-cdc-docs-stable/) - streaming data integration tool powered by Apache Flink.
* [Fluentd](http://www.fluentd.org) - tool to collect events and logs.
* [Google Photon](https://research.google.com/pubs/pub41318.html) - geographically distributed system for joining multiple continuously flowing streams of data in real-time with high scalability and low latency.
* [Graylog](https://www.graylog.org/) - log management platform for collecting, storing, searching, and alerting on machine data.
* [Hevo](https://hevodata.com/) - managed data pipeline platform for moving data from databases, SaaS apps, cloud storage, SDKs, and streaming services.
* [Hightouch](https://hightouch.com/) - reverse ETL platform for syncing warehouse data into business applications.
* [Kestrel](https://github.com/papertrail/kestrel) - distributed message queue system.
* [LinkedIn Databus](https://engineering.linkedin.com/data) - stream of change capture events for a database.
* [Logstash](https://www.elastic.co/products/logstash) - a tool for managing events and logs.
* [Metricbeat](https://www.elastic.co/beats/metricbeat) - lightweight shipper for system and service metrics.
* [StreamSets Data Collector](https://github.com/streamsets/datacollector) - continuous big data ingest infrastructure with a simple to use IDE.
* [Alooma](https://www.alooma.com/integrations/mysql) - data pipeline as a service enabling moving data sources such as MySQL into data warehouses.

## Data Quality and Observability

* [DataKitchen Open Source Data Observability](https://docs.datakitchen.io/observability/get-started/) - open-source data observability for monitoring data journeys, data quality, and pipeline events.
* [Great Expectations](https://greatexpectations.io/) - open-source framework for validating, documenting, and testing data quality.
* [OpenLineage](https://openlineage.io/) - open standard and reference implementation for collecting lineage metadata from data pipelines.
* [Soda Core](https://docs.soda.io/soda-core/overview-main.html) - open-source Python library and CLI for data quality tests.

## Service Programming

* [Spotify Luigi](https://github.com/spotify/luigi) ⭐ 18,766 | 🐛 167 | 🌐 Python | 📅 2026-07-18 - a Python package for building complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.
* [Mara](https://github.com/mara/data-integration) ⭐ 2,089 | 🐛 26 | 🌐 Python | 📅 2023-12-15 - A lightweight opinionated ETL framework, halfway between plain scripts and Apache Airflow
* [Twitter Elephant Bird](https://github.com/twitter/elephant-bird) ⭐ 1,133 | 🐛 87 | 🌐 Java | 📅 2023-04-10 - libraries for working with LZOP-compressed data.
* [Spring XD](https://github.com/spring-projects/spring-xd) ⚠️ Archived - distributed and extensible system for data ingestion, real time analytics, batch processing, and data export.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) ⭐ 326 | 🐛 32 | 🌐 Scala | 📅 2026-04-13 - a service for exposing Apache Spark analytics jobs and machine learning models as realtime, batch or reactive web services.
* [Akka Toolkit](http://akka.io/) - runtime for distributed, and fault tolerant event-driven applications on the JVM.
* [Apache Avro](http://avro.apache.org/) - data serialization system.
* [Apache Curator](http://curator.apache.org/) - Java libraries for Apache ZooKeeper.
* [Apache Karaf](http://karaf.apache.org/) - OSGi runtime that runs on top of any OSGi framework.
* [Apache Thrift](http://thrift.apache.org//) - framework to build binary protocols.
* [Apache Zookeeper](http://zookeeper.apache.org/) - centralized service for process management.
* [Google Chubby](https://research.google.com/archive/chubby.html) - a lock service for loosely-coupled distributed systems.
* [Linkedin Norbert](https://engineering.linkedin.com/data) - cluster manager.
* [OpenMPI](https://www.open-mpi.org/) - message passing framework.
* [Serf](https://www.serf.io/) - decentralized solution for service discovery and orchestration.
* [Twitter Finagle](https://twitter.github.io/finagle/) - asynchronous network stack for the JVM.

## Scheduling

* [Apache Airflow](https://github.com/apache/incubator-airflow) ⭐ 46,552 | 🐛 1,878 | 🌐 Python | 📅 2026-08-20 - a platform to programmatically author, schedule and monitor workflows.
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,032 | 🐛 2,595 | 🌐 Python | 📅 2026-08-19 - a data orchestrator for machine learning, analytics, and ETL.
* [Cronicle](https://github.com/jhuckaby/Cronicle) ⭐ 5,801 | 🐛 333 | 🌐 JavaScript | 📅 2026-08-15 - Distributed, easy to install, NodeJS based, task scheduler
* [Sparrow](https://github.com/radlab/sparrow) ⚠️ Archived - scheduling platform.
* [Schedoscope](https://github.com/ottogroup/schedoscope) ⚠️ Archived - Scala DSL for agile scheduling of Hadoop jobs.
* [Apache Aurora](http://aurora.apache.org/) - is a service scheduler that runs on top of Apache Mesos.
* [Apache Falcon](http://falcon.apache.org/) - data management framework.
* [Apache Oozie](http://oozie.apache.org/) - workflow job scheduler.
* [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-introduction) - cloud-based pipeline orchestration for on-prem, cloud and HDInsight
* [Chronos](http://mesos.github.io/chronos/) - distributed and fault-tolerant scheduler.
* [Linkedin Azkaban](https://azkaban.github.io/) - batch workflow job scheduler.

## Machine Learning

* [TensorFlow](https://github.com/tensorflow/tensorflow) ⭐ 197,096 | 🐛 3,117 | 🌐 C++ | 📅 2026-08-20 - Library from Google for machine learning using data flow graphs.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 66,978 | 🐛 2,119 | 🌐 Python | 📅 2026-08-20 - scikit-learn: machine learning in Python.
* [Keras](https://github.com/fchollet/keras) ⭐ 64,240 | 🐛 227 | 🌐 Python | 📅 2026-08-20 - An intuitive neural net API inspired by Torch that runs atop Theano and Tensorflow.
* [convnetjs](https://github.com/karpathy/convnetjs) ⭐ 11,195 | 🐛 75 | 🌐 JavaScript | 📅 2023-01-07 - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) ⭐ 8,706 | 🐛 1 | 🌐 C++ | 📅 2026-08-18 - learning system sponsored by Microsoft and Yahoo!.
* [brain](https://github.com/harthur/brain) ⚠️ Archived - Neural networks in JavaScript.
* [H2O](https://github.com/h2oai/h2o-3/) ⭐ 7,495 | 🐛 2,882 | 🌐 Jupyter Notebook | 📅 2026-08-20 - statistical, machine learning and math runtime with Hadoop. R and Python.
* [Feast](https://github.com/gojek/feast) ⭐ 7,223 | 🐛 389 | 🌐 Python | 📅 2026-08-20 - A feature store for the management, discovery, and access of machine learning features. Feast provides a consistent view of feature data for both model training and model serving.
* [nupic](https://github.com/numenta/nupic) ⭐ 6,351 | 🐛 465 | 🌐 Python | 📅 2024-12-03 - Numenta Platform for Intelligent Computing: a brain-inspired machine intelligence platform, and biologically accurate neural network based on cortical learning algorithms.
* [Aim](https://github.com/aimhubio/aim) ⭐ 6,237 | 🐛 468 | 🌐 Python | 📅 2026-08-19 - open-source AI metadata tracker for experiments and training runs.
* [ML Workspace](https://github.com/ml-tooling/ml-workspace) ⭐ 3,543 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-07-26 - All-in-one web-based IDE specialized for machine learning and data science.
* [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) ⭐ 2,993 | 🐛 30 | 🌐 Python | 📅 2026-05-30 - a temporal extension library for PyTorch Geometric .
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) ⭐ 2,285 | 🐛 12 | 🌐 Python | 📅 2024-07-17 - An unsupervised machine learning library for graph structured data. Python
* [Oryx](https://github.com/OryxProject/oryx) ⚠️ Archived - Lambda architecture on Apache Spark, Apache Kafka for real-time large scale machine learning.
* [BidMach](https://github.com/BIDData/BIDMach) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - CPU and GPU-accelerated Machine Learning Library.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) ⭐ 899 | 🐛 1 | 🌐 Objective-C | 📅 2016-09-30 - Fast multilayer perceptron neural network library for iOS and Mac OS X.
* [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur) ⭐ 714 | 🐛 7 | 🌐 Python | 📅 2025-12-20 - A subsampling library for graph structured data. Python
* [Decider](https://github.com/danielsdeleo/Decider) ⭐ 383 | 🐛 2 | 🌐 Ruby | 📅 2017-04-06 - Flexible and Extensible Machine Learning in Ruby.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) ⚠️ Archived - scalable Machine Learning in Scalding.
* [isolation-forest](https://github.com/linkedin/isolation-forest) ⭐ 262 | 🐛 1 | 🌐 Scala | 📅 2026-08-04 - distributed Spark and Scala implementation of isolation forest for unsupervised outlier detection.
* [Shapley](https://github.com/benedekrozemberczki/shapley) ⭐ 227 | 🐛 1 | 🌐 Python | 📅 2026-01-01 - A data-driven framework to quantify the value of classifiers in a machine learning ensemble.
* [Velox](https://github.com/amplab/velox-modelserver) ⭐ 110 | 🐛 23 | 🌐 Scala | 📅 2017-04-17 - System for serving machine learning predictions.
* [Lambdo](https://github.com/johnsonc/lambdo) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-09-10 - Lambdo is a workflow engine which significantly simplifies the analysis process by unifying feature engineering and machine learning operations.
* [Azure ML Studio](https://studio.azureml.net/) - Cloud-based AzureML, R, Python Machine Learning platform
* [Concurrent Pattern](http://www.cascading.org/projects/pattern/) - machine learning library for Cascading.
* [DataVec](https://github.com/deeplearning4j/DataVec) - A vectorization and data preprocessing library for deep learning in Java and Scala. Part of the Deeplearning4j ecosystem.
* [Deeplearning4j](https://github.com/deeplearning4j) - Fast, open deep learning for the JVM (Java, Scala, Clojure). A neural network configuration layer powered by a C++ library. Uses Spark and Hadoop to train nets on multiple GPUs and CPUs.
* [ENCOG](http://www.heatonresearch.com/encog/) - machine learning framework that supports a variety of advanced algorithms, as well as support classes to normalize and process data.
* [etcML](http://www.etcml.com/) - text classification with machine learning.
* [GraphLab Create](https://dato.com/products/create/) - A machine learning platform in Python with a broad collection of ML toolkits, data engineering, and deployment tools.
* [Mahout](http://mahout.apache.org/) - An Apache-backed machine learning library for Hadoop.
* [MLbase](http://www.mlbase.org/) - distributed machine learning libraries for the BDAS stack.
* [MOA](http://moa.cms.waikato.ac.nz) - MOA performs big data stream mining in real time, and large scale machine learning.
* [MonkeyLearn](https://monkeylearn.com/) - Text mining made easy. Extract and classify data from text.
* [ND4J](https://github.com/deeplearning4j/nd4j) - A matrix library for the JVM. Numpy for Java.
* [Neptune](https://neptune.ai/) - experiment tracking and model registry for research and production machine learning teams.
* [PredictionIO](http://predictionio.incubator.apache.org/index.html) - machine learning server built on Hadoop, Mahout and Cascading.
* [RL4J](https://github.com/deeplearning4j/rl4j) - Reinforcement learning for Java and Scala. Includes Deep-Q learning and A3C algorithms, and integrates with Open AI's Gym. Runs in the Deeplearning4j ecosystem.
* [SAMOA](http://samoa.incubator.apache.org/) - distributed streaming machine learning framework.
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) - a Spark implementation of some common machine learning (ML) functionality.
* [Sibyl](https://users.soe.ucsc.edu/~niejiazhong/slides/chandra.pdf) - System for Large Scale Machine Learning at Google.
* [Theano](https://github.com/theano) - A Python-focused machine learning library supported by the University of Montreal.
* [Torch](https://github.com/torch) - A deep learning library with a Lua API, supported by NYU and Facebook.
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) - suite of machine learning software.

## Benchmarking

* [Intel HiBench](https://github.com/intel-hadoop/HiBench) ⚠️ Archived - a Hadoop benchmark suite.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) ⭐ 128 | 🐛 3 | 🌐 Java | 📅 2014-05-29 - real-world big data workload benchmark.
* [UCSB](https://github.com/unum-cloud/ucsb) ⭐ 59 | 🐛 3 | 🌐 C++ | 📅 2023-09-08 - extended Yahoo Cloud Serving Benchmark for NoSQL databases.
* [Estuary Benchmark Report](https://github.com/estuary/estuary-warehouse-benchmark) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-07-23 - reproducible, vendor-neutral data warehouse benchmark.
* [Apache JMeter](https://jmeter.apache.org/) - load testing tool for measuring performance of services and distributed systems.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) - benchmark suite for MapReduce applications.
* [Yahoo Gridmix3](http://yahoohadoop.tumblr.com/post/98294079296/gridmix3-emulating-production-workload-for) - Hadoop cluster benchmarking from Yahoo engineer team.
* [Deeplearning4j Benchmarks](https://github.com/deeplearning4j/dl4j-benchmark)

## Security

* [BDA](https://github.com/kotobukki/BDA/) ⚠️ Archived - The vulnerability detector for Hadoop and Spark
* [FileShot](https://github.com/FileShot/FileShotZKE) ⭐ 30 | 🐛 1 | 🌐 HTML | 📅 2026-06-03 - zero-knowledge encrypted file transfer for sharing large datasets.
* [Apache Ranger](http://ranger.apache.org/) - Central security admin & fine-grained authorization for Hadoop
* [Apache Eagle](http://eagle.apache.org/) - real time monitoring solution
* [Apache Knox Gateway](http://knox.apache.org/) - single point of secure access for Hadoop clusters.
* [Apache Sentry](http://incubator.apache.org/projects/sentry.html) - security module for data stored in Hadoop.

## System Deployment

* [Marathon](https://github.com/mesosphere/marathon) ⚠️ Archived - Mesos framework for long-running services.
* [Linkis](https://github.com/WeBankFinTech/Linkis) ⭐ 3,405 | 🐛 174 | 🌐 Java | 📅 2026-08-19 - Linkis helps easily connect to various back-end computation/storage engines.
* [Apache Slider](https://github.com/apache/incubator-slider) ⚠️ Archived - is a YARN application to deploy existing distributed applications on YARN.
* [Apache Ambari](http://ambari.apache.org/) - operational framework for Hadoop management.
* [Apache Bigtop](http://bigtop.apache.org//) - system deployment framework for the Hadoop ecosystem.
* [Apache Helix](http://helix.apache.org/) - cluster management framework.
* [Apache Mesos](http://mesos.apache.org/) - cluster manager.
* [Apache Whirr](http://whirr.apache.org/) - set of libraries for running cloud services.
* [Apache YARN](https://hortonworks.com/hadoop/yarn/) - Cluster manager.
* [Brooklyn](http://brooklyncentral.github.io/) - library that simplifies application deployment and management.
* [Buildoop](http://buildoop.github.io/) - Similar to Apache BigTop based on Groovy language.
* [Cloudera HUE](http://gethue.com/) - web application for interacting with Hadoop.
* [Facebook Prism](http://www.wired.com/2012/08/facebook-prism/) - multi datacenters replication system.
* [Google Borg](https://www.wired.com/2013/03/google-borg-twitter-mesos/all/) - job scheduling and monitoring system.
* [Google Omega](https://www.youtube.com/watch?v=0ZFMlO98Jkc) - job scheduling and monitoring system.
* [Hortonworks HOYA](https://hortonworks.com/blog/introducing-hoya-hbase-on-yarn/) - application that can deploy HBase cluster on YARN.
* [Kubernetes](https://kubernetes.io/) - a system for automating deployment, scaling, and management of containerized applications.
* [Terraform](https://www.terraform.io/) - infrastructure as code tool for provisioning and managing cloud and on-premises infrastructure.

## Applications

* [ElastAert](https://github.com/Yelp/elastalert) ⭐ 7,987 | 🐛 1,401 | 🌐 Python | 📅 2024-08-07 - ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in ElasticSearch.
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,028 | 🐛 59 | 🌐 Scala | 📅 2026-06-26 - enterprise-strength web and event analytics, powered by Hadoop, Kinesis, Redshift and Postgres.
* [Atlas](https://github.com/Netflix/atlas) ⭐ 3,562 | 🐛 8 | 🌐 Scala | 📅 2026-08-20 - a backend for managing dimensional time series data.
* [Kapacitor](https://github.com/influxdata/kapacitor) ⭐ 2,374 | 🐛 833 | 🌐 Go | 📅 2026-08-10 - an open source framework for processing, monitoring, and alerting on time series data.
* [Eventhub](https://github.com/Codecademy/EventHub) ⭐ 1,335 | 🐛 1 | 🌐 Java | 📅 2022-04-05 - open source event analytics platform.
* [AthenaX](https://github.com/uber/AthenaX) ⚠️ Archived - a streaming analytics platform that enables users to run production-quality, large scale streaming analytics using Structured Query Language (SQL).
* [SnappyData](https://github.com/SnappyDataInc/snappydata) ⭐ 1,033 | 🐛 117 | 🌐 Scala | 📅 2022-11-21 - a distributed in-memory data store for real-time operational analytics, delivering stream analytics, OLTP (online transaction processing) and OLAP (online analytical processing) built on Spark in a single integrated cluster.
* [411](https://github.com/etsy/411) ⚠️ Archived - an web application for alert management resulting from scheduled searches into Elasticsearch.
* [Hermes](https://github.com/allegro/hermes) ⭐ 865 | 🐛 7 | 🌐 Java | 📅 2026-08-18 - asynchronous message broker built on top of Kafka.
* [Rakam](https://github.com/rakam-io/rakam) ⭐ 791 | 🐛 13 | 🌐 Java | 📅 2021-11-13 - open-source real-time custom analytics platform powered by Postgresql, Kinesis and PrestoDB.
* [Substation](https://github.com/brexhq/substation) ⭐ 403 | 🐛 3 | 🌐 Go | 📅 2026-01-20 - Substation is a cloud native data pipeline and transformation toolkit written in Go.
* [Adobe spindle](https://github.com/adobe-research/spindle) ⭐ 330 | 🐛 2 | 🌐 JavaScript | 📅 2015-03-28 - Next-generation web analytics processing with Scala, Spark, and Parquet.
* [PivotalR](https://github.com/pivotalsoftware/PivotalR) ⚠️ Archived - R on Pivotal HD / HAWQ and PostgreSQL.
* [Apache Metron](http://metron.apache.org/) - a platform that integrates a variety of open source big data technologies in order to offer a centralized tool for security monitoring and analysis.
* [Apache Nutch](http://nutch.apache.org/) - open source web crawler.
* [Apache OODT](http://oodt.apache.org/) - capturing, processing and sharing of data for NASA's scientific archives.
* [Apache Tika](https://tika.apache.org/) - content analysis toolkit.
* [Argus](https://github.com/salesforce/Argus) - Time series monitoring and alerting platform.
* [Countly](https://count.ly/) - open source mobile and web analytics platform, based on Node.js & MongoDB.
* [Comet](https://www.comet.com/site/) - Comet provides an end-to-end model evaluation platform for AI developers, with best in class LLM evaluations, experiment tracking, and production monitoring.
* [Domino](https://www.dominodatalab.com/) - Run, scale, share, and deploy models — without any infrastructure.
* [Eclipse BIRT](http://www.eclipse.org/birt/) - Eclipse-based reporting system.
* [Gigasheet](https://www.gigasheet.com/) - cloud spreadsheet for exploring and analyzing large datasets.
* [HASH](https://hash.ai) - open source simulation and visualization platform.
* [Hunk](https://www.splunk.com/en_us/download/hunk.html) - Splunk analytics for Hadoop.
* [Indicative](https://www.indicative.com/) - Web & mobile analytics tool, with data warehouse (AWS, BigQuery) integration.
* [Jupyter](https://jupyter.org/) - Notebook and project application for interactive data science and scientific computing across all programming languages.
* [MADlib](http://madlib.incubator.apache.org/community/) - data-processing library of an RDBMS to analyze data.
* [Kylin](http://kylin.apache.org/) - open source Distributed Analytics Engine from eBay.
* [Opik](https://www.comet.com/site/products/opik/) - Debug, evaluate, and monitor your LLM applications, RAG systems, and agentic workflows with comprehensive tracing, automated evaluations, and production-ready dashboards.
* [Qubole](https://www.qubole.com/) - auto-scaling Hadoop cluster, built-in data connectors.
* [SparkR](http://amplab-extras.github.io/SparkR-pkg/) - R frontend for Spark.
* [Splunk](https://www.splunk.com/) - analyzer for machine-generated data.
* [Sumo Logic](https://www.sumologic.com/) - cloud based analyzer for machine-generated data.
* [Talend](http://www.talend.com/products/big-data/) - unified open source environment for YARN, Hadoop, HBASE, Hive, HCatalog & Pig.

## Search engine and framework

* [Facebook Faiss](https://github.com/facebookresearch/faiss) ⭐ 40,774 | 🐛 285 | 🌐 C++ | 📅 2026-08-19 - is a library for efficient similarity search and clustering of dense vectors. It contains algorithms that search in sets of vectors of any size, up to ones that possibly do not fit in RAM. It also contains supporting code for evaluation and parameter tuning. Faiss is written in C++ with complete wrappers for Python/numpy.
* [Annoy](https://github.com/spotify/annoy) ⭐ 14,289 | 🐛 84 | 🌐 C++ | 📅 2025-10-29 - is a C++ library with Python bindings to search for points in space that are close to a given query point. It also creates large read-only file-based data structures that are mmapped into memory so that many processes may share the same data.
* [Elassandra](https://github.com/strapdata/elassandra) ⭐ 1,714 | 🐛 60 | 🌐 Java | 📅 2026-05-17 - is a fork of Elasticsearch modified to run on top of Apache Cassandra in a scalable and resilient peer-to-peer architecture.
* [LinkedIn Cleo](https://github.com/linkedin/cleo) ⭐ 567 | 🐛 8 | 🌐 Java | 📅 2013-11-13 - is a flexible software library for enabling rapid development of partial, out-of-order and real-time typeahead search.
* [LinkedIn Zoie](https://github.com/senseidb/zoie) ⭐ 369 | 🐛 16 | 🌐 Java | 📅 2022-12-15 - is a realtime search/indexing system written in Java.
* [Apache Lucene](http://lucene.apache.org/) - Search engine library.
* [Apache Solr](http://lucene.apache.org/solr/) - Search platform for Apache Lucene.
* [ElasticSearch](https://www.elastic.co/) - Search and analytics engine based on Apache Lucene.
* [Enigma.io](https://www.enigma.com/) – Freemium robust web application for exploring, filtering, analyzing, searching and exporting massive datasets scraped from across the Web.
* [Google Caffeine](https://googleblog.blogspot.it/2010/06/our-new-search-index-caffeine.html) - continuous indexing system.
* [Google Percolator](https://research.google.com/pubs/pub36726.html) - continuous indexing system.
* [HBase Coprocessor](https://blogs.apache.org/hbase/entry/coprocessor_introduction) - implementation of Percolator, part of HBase.
* [Lily HBase Indexer](http://ngdata.github.io/hbase-indexer/) - quickly and easily search for any content stored in HBase.
* [LinkedIn Bobo](http://senseidb.github.io/bobo/) - is a Faceted Search implementation written purely in Java, an extension to Apache Lucene.
* [LinkedIn Galene](https://engineering.linkedin.com/search/did-you-mean-galene) - search architecture at LinkedIn.
* [MG4J](http://mg4j.di.unimi.it/) - MG4J (Managing Gigabytes for Java) is a full-text search engine for large document collections written in Java. It is highly customisable, high-performance and provides state-of-the-art features and new research algorithms.
* [Sphinx Search Server](http://sphinxsearch.com/) - fulltext search engine.
* [Vespa](http://vespa.ai/) - is an engine for low-latency computation over large data sets. It stores and indexes your data such that queries, selection and processing over the data can be performed at serving time.

## MySQL forks and evolutions

* [Amazon RDS](https://aws.amazon.com/rds/) - MySQL databases in Amazon's cloud.
* [Drizzle](http://www.drizzle.org/) - evolution of MySQL 6.0.
* [Google Cloud SQL](https://cloud.google.com/sql/docs/) - MySQL databases in Google's cloud.
* [MariaDB](https://mariadb.org/) - enhanced, drop-in replacement for MySQL.
* [MySQL Cluster](https://www.mysql.com/products/cluster/) - MySQL implementation using NDB Cluster storage engine.
* [Percona Server](https://www.percona.com/software/mysql-database/percona-server) - enhanced, drop-in replacement for MySQL.
* [ProxySQL](https://github.com/renecannao/proxysql) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2025-11-23 - High Performance Proxy for MySQL.
* [TokuDB](https://www.percona.com/) - TokuDB is a storage engine for MySQL and MariaDB.
* [WebScaleSQL](http://webscalesql.org/) - is a collaboration among engineers from several companies that face similar challenges in running MySQL at scale.

## PostgreSQL forks and evolutions

* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) - hybrid of MapReduce and DBMS.
* [IBM Netezza](http://www-01.ibm.com/software/data/netezza/) - high-performance data warehouse appliances.
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [RecDB](http://www-users.cs.umn.edu/~sarwat/RecDB/) - Open Source Recommendation Engine Built Entirely Inside PostgreSQL.
* [Stado](http://www.stormdb.com/community/stado) - open source MPP database system solely targeted at data warehousing and data mart applications.
* [Yahoo Everest](https://www.scribd.com/doc/3159239/70-Everest-PGCon-RT) - multi-peta-byte database / MPP derived by PostgreSQL.
* [TimescaleDB](http://www.timescale.com/) - An open-source time-series database optimized for fast ingest and complex queries
* [PipelineDB](https://www.pipelinedb.com/) - The Streaming SQL Database. An open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables

## Memcached forks and evolutions

* [Twemproxy](https://github.com/twitter/twemproxy) ⭐ 12,335 | 🐛 194 | 🌐 C | 📅 2024-03-29 - A fast, light-weight proxy for memcached and redis.
* [Twitter Fatcache](https://github.com/twitter/fatcache) ⚠️ Archived - key/value cache for flash storage.
* [Twitter Twemcache](https://github.com/twitter/twemcache) ⚠️ Archived - fork of Memcache.
* [Facebook McDipper](https://www.facebook.com/notes/facebook-engineering/mcdipper-a-key-value-cache-for-flash-storage/10151347090423920) - key/value cache for flash storage.
* [Facebook Memcached](https://www.facebook.com/notes/facebook-engineering/scaling-memcache-at-facebook/10151411410803920) - fork of Memcache.

## Embedded Databases

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,343 | 🐛 402 | 🌐 C++ | 📅 2026-03-11 - a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
* [HanoiDB](https://github.com/krestenkrab/hanoidb) ⭐ 313 | 🐛 14 | 🌐 Erlang | 📅 2016-08-07 - Erlang LSM BTree Storage.
* [Actian PSQL](http://www.actian.com/products/operational-databases/) - ACID-compliant DBMS developed by Pervasive Software, optimized for embedding in applications.
* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) - a software library that provides a high-performance embedded database for key/value data.
* [LMDB](https://symas.com/mdb/) - ultra-fast, ultra-compact key-value embedded data store developed by Symas.
* [RocksDB](http://rocksdb.org/) - embeddable persistent key-value store for fast storage based on LevelDB.

## Business Intelligence

* [Metabase](https://github.com/metabase/metabase) ⭐ 48,849 | 🐛 4,377 | 🌐 Clojure | 📅 2026-08-20 - The simplest, fastest way to get business intelligence and analytics to everyone in your company.
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,061 | 🐛 1,236 | 🌐 TypeScript | 📅 2026-08-20 - The open source Looker alternative built on dbt
* [Blazer](https://github.com/ankane/blazer) ⭐ 4,795 | 🐛 32 | 🌐 Ruby | 📅 2026-08-15 - business intelligence made simple.
* [BIME Analytics](https://www.bimeanalytics.com/?lang=en) - business intelligence platform in the cloud.
* [Chartio](https://chartio.com) - lean business intelligence platform to visualize and explore your data.
* [Count](https://count.co) - notebook-based anlytics and visualisation platform using SQL or drag-and-drop.
* [datapine](https://www.datapine.com/) - self-service business intelligence tool in the cloud.
* [Dekart](https://dekart.xyz/) - Large scale geospatial analytics for Google BigQuery based on Kepler.gl.
* [GoodData](https://www.gooddata.com/) - platform for data products and embedded analytics.
* [Jaspersoft](https://www.jaspersoft.com/) - powerful business intelligence suite.
* [Jedox Palo](https://www.jedox.com/en/) - customisable Business Intelligence platform.
* [Jethrodata](https://jethro.io/) - Interactive Big Data Analytics.
* [intermix.io](https://intermix.io/) - Performance Monitoring for Amazon Redshift
* [Microsoft](http://www.microsoft.com/en-us/server-cloud/solutions/business-intelligence/default.aspx) - business intelligence software and platform.
* [Microstrategy](https://www.microstrategy.com/) - software platforms for business intelligence, mobile intelligence, and network applications.
* [Numeracy](https://numeracy.co/) - Fast, clean SQL client and business intelligence.
* [Pentaho](http://www.pentaho.com/) - business intelligence platform.
* [Qlik](http://www.qlik.com/us/) - business intelligence and analytics platform.
* [Query.me](https://query.me/) - collaborative SQL notebooks for querying, scheduling, and sharing reporting workflows.
* [Redash](https://redash.io/) - Open source business intelligence platform, supporting multiple data sources and planned queries.
* [Datapallas](https://datapallas.com/) - BI and data platform with AI exploration, dashboards, and pixel-perfect report generation; formerly ReportBurster.
* [Saiku Analytics](https://www.meteorite.bi/) - Open source analytics platform.
* [Knowage](https://www.knowage-suite.com/) - open source business intelligence platform. (former [SpagoBi](http://www.spagobi.org/))
* [SparklineData SNAP](http://sparklinedata.com/) - modern B.I platform powered by Apache Spark.
* [Tableau](https://www.tableau.com/) - business intelligence platform.
* [Zoomdata](https://www.zoomdata.com/) - Big Data Analytics.

## Data Visualization

* [Superset](https://github.com/apache/incubator-superset) ⭐ 74,321 | 🐛 628 | 🌐 Python | 📅 2026-08-20 - a data exploration platform designed to be visual, intuitive and interactive, making it easy to slice, dice and visualize data and perform analytics at the speed of thought.
* [Echarts](https://github.com/ecomfe/echarts) ⭐ 67,102 | 🐛 1,556 | 🌐 TypeScript | 📅 2026-08-04 - Baidus enterprise charts.
* [Redash](https://github.com/getredash/redash) ⭐ 28,759 | 🐛 801 | 🌐 Python | 📅 2026-08-18 - open-source platform to query and visualize data.
* [Dash](https://github.com/plotly/dash) ⭐ 24,379 | 🐛 539 | 🌐 Python | 📅 2026-08-19 - Analytical Web Apps for Python, R, Julia, and Jupyter. Built on top of plotly, no JS required
* [Matplotlib](https://github.com/matplotlib/matplotlib) ⭐ 23,095 | 🐛 1,479 | 🌐 Python | 📅 2026-08-19 - plotting with Python.
* [Plotly.js](https://github.com/plotly/plotly.js) ⭐ 18,297 | 🐛 845 | 🌐 JavaScript | 📅 2026-08-20 The open source javascript graphing library that powers plotly.
* [Sigma.js](https://github.com/jacomyal/sigma.js) ⭐ 12,140 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-18 - JavaScript library dedicated to graph drawing.
* [Vega](https://github.com/vega/vega) ⭐ 11,964 | 🐛 470 | 🌐 JavaScript | 📅 2026-08-14 - a visualization grammar.
* [Gephi](https://github.com/gephi/gephi) ⭐ 6,617 | 🐛 520 | 🌐 Java | 📅 2026-08-19 - An award-winning open-source platform for visualizing and manipulating large graphs and network connections. It's like Photoshop, but for graphs. Available for Windows and Mac OS X.
* [Freeboard](https://github.com/Freeboard/freeboard) ⭐ 6,503 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-23 - pen source real-time dashboard builder for IOT and other web mashups.
* [Cubism](https://github.com/square/cubism) ⭐ 4,926 | 🐛 42 | 🌐 JavaScript | 📅 2025-04-01 - JavaScript library for time series visualization.
* [Peity](https://github.com/benpickles/peity) ⭐ 4,213 | 🐛 23 | 🌐 HTML | 📅 2024-04-11 - Progressive SVG bar, line and pie charts.
* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio) ⭐ 3,261 | 🐛 362 | 🌐 Java | 📅 2025-11-04 - one-stop data application development management portal.
* [Airpal](https://github.com/airbnb/airpal) ⚠️ Archived - Web UI for PrestoDB.
* [Arbor](https://github.com/samizdatco/arbor) ⭐ 2,658 | 🐛 56 | 🌐 JavaScript | 📅 2020-04-10 - graph visualization library using web workers and jQuery.
* [Recline](https://github.com/okfn/recline) ⭐ 2,342 | 🐛 73 | 🌐 TypeScript | 📅 2026-08-20 - simple but powerful library for building data applications in pure Javascript and HTML.
* [Envisionjs](https://github.com/HumbleSoftware/envisionjs) ⭐ 1,554 | 🐛 24 | 🌐 JavaScript | 📅 2020-04-10 - dynamic HTML5 visualization.
* [D3.compose](https://github.com/CSNW/d3.compose) ⭐ 695 | 🐛 18 | 🌐 JavaScript | 📅 2022-12-10 - Compose complex, data-driven visualizations from reusable charts and components.
* [Banana](https://github.com/LucidWorks/banana) ⭐ 673 | 🐛 109 | 🌐 JavaScript | 📅 2026-05-28 - visualize logs and time-stamped data stored in Solr. Port of Kibana.
* [Zeppelin](https://github.com/ZEPL/zeppelin) ⭐ 404 | 🐛 81 | 📅 2017-07-05 - a notebook-style collaborative data analysis.
* [Chartist.js](https://github.com/gionkunz/chartist-js) ⭐ 96 | 🐛 11 | 🌐 JavaScript | 📅 2024-05-06 - another open source HTML5 Charts visualization.
* [Bloomery](https://github.com/ufukomer/bloomery) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2017-03-17 - Web UI for Impala.
* [AnyChart](http://www.anychart.com) - fast, simple and flexible JavaScript (HTML5) charting library featuring pure JS API.
* [Bokeh](http://bokeh.pydata.org/en/latest/) - A powerful Python interactive visualization library that targets modern web browsers for presentation, with the goal of providing elegant, concise construction of novel graphics in the style of D3.js, but also delivering this capability with high-performance interactivity over very large or streaming datasets.
* [C3](http://c3js.org/) - D3-based reusable chart library
* [CartoDB](https://github.com/CartoDB/cartodb) - open-source or freemium hosting for geospatial databases with powerful front-end editing capabilities and a robust API.
* [chartd](http://chartd.co/) - responsive, retina-compatible charts with just an img tag.
* [Chart.js](http://www.chartjs.org/) - open source HTML5 Charts visualizations.
* [Crossfilter](http://square.github.io/crossfilter/) -  JavaScript library for exploring large multivariate datasets in the browser. Works well with dc.js and d3.js.
* [Cytoscape](http://cytoscape.github.io/) - JavaScript library for visualizing complex networks.
* [DC.js](http://dc-js.github.io/dc.js/) - Dimensional charting built to work natively with crossfilter rendered using d3.js. Excellent for connecting charts/additional metadata to hover events in D3.
* [D3](https://d3js.org/) - javaScript library for manipulating documents.
* [D3Plus](http://d3plus.org) - A fairly robust set of reusable charts and styles for d3.js.
* [Dekart](https://dekart.xyz/) - Large scale geospatial analytics for Google BigQuery based on Kepler.gl.
* [DevExtreme React Chart](https://devexpress.github.io/devextreme-reactive/react/chart/) - High-performance plugin-based React chart for Bootstrap and Material Design.
* [Flexmonster Pivot Table & Charts](https://www.flexmonster.com/) - JavaScript component for pivot tables, charts, and web reporting.
* [FnordMetric](https://metrictools.org/) - write SQL queries that return SVG charts rather than tables
* [Frappe Charts](https://frappe.io/charts) - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
* [Google Charts](https://developers.google.com/chart/) - simple charting API.
* [Grafana](https://grafana.com/) - graphite dashboard frontend, editor and graph composer.
* [Graphite](http://graphiteapp.org/) - scalable Realtime Graphing.
* [Highcharts](https://www.highcharts.com/) - simple and flexible charting API.
* [IPython](http://ipython.org/) - provides a rich architecture for interactive computing.
* [Kibana](https://www.elastic.co/products/kibana) - visualize logs and time-stamped data
* [Lumify](http://lumify.io/) - open source big data analysis and visualization platform
* [Metricsgraphic.js](https://metricsgraphicsjs.org/) - a library built on top of D3 that is optimized for time-series data
* [NVD3](http://nvd3.org/) - chart components for d3.js.
* [Plot.ly](https://plot.ly/) - Easy-to-use web service that allows for rapid creation of complex charts, from heatmaps to histograms. Upload data to create and style charts with Plotly's online spreadsheet. Fork others' plots.
* [ReCharts](http://recharts.org/) - A composable charting library built on React components
* [Shiny](http://shiny.rstudio.com/) - a web application framework for R.
* [WebDataRocks](https://www.webdatarocks.com/) - free web pivot table component for embedding analytics in applications.
* [Zing Charts](https://www.zingchart.com/) - JavaScript charting library for big data.

## Internet of things and sensor data

* [Apache Edgent (Incubating)](http://edgent.apache.org/) - a programming model and micro-kernel style runtime that can be embedded in gateways and small footprint edge devices enabling local, real-time, analytics on the edge devices.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - Cloud-based bi-directional monitoring and messaging hub
* [TempoIQ](https://www.tempoiq.com/) - Cloud-based sensor analytics.
* [2lemetry](http://2lemetry.com/) - Platform for Internet of things.
* [Pubnub](https://www.pubnub.com/) - Data stream network
* [ThingWorx](https://www.thingworx.com/) - Rapid development and connection of intelligent systems
* [IFTTT](https://ifttt.com/) - If this then that
* [Evrything](https://evrythng.com/)- Making products smart
* [NetLytics](https://github.com/marty90/netlytics/) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2018-02-01 - Analytics platform to process network data on Spark.
* [Ably](https://ably.com/) - Pub/sub messaging platform for IoT

## Interesting Readings

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/) - Benchmark of Redshift, Hive, Shark, Impala and Stiger/Tez.
* [NoSQL Comparison](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis) - Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris comparison.
* [Monitoring Kafka performance](https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics?ref=awesome) - Guide to monitoring Apache Kafka, including native methods for metrics collection.
* [Monitoring Hadoop performance](https://www.datadoghq.com/blog/monitor-hadoop-metrics?ref=awesome) - Guide to monitoring Hadoop, with an overview of Hadoop architecture, and native methods for metrics collection.
* [Monitoring Cassandra performance](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/?ref=awesome) - Guide to monitoring Cassandra, including native methods for metrics collection.

## Interesting Papers

### 2015 - 2016

* [2015](http://www.vldb.org/pvldb/vol8/p1804-ching.pdf) - **Facebook** - One Trillion Edges: Graph Processing at Facebook-Scale.

### 2013 - 2014

* [2014](http://infolab.stanford.edu/~ullman/mmds/book.pdf) - **Stanford** - Mining of Massive Datasets.
* [2013](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/03/eurosys13-paper83.pdf) - **AMPLab** - Presto: Distributed Machine Learning and Graph Processing with Sparse Matrices.
* [2013](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/01/dmx1.pdf) - **AMPLab** - MLbase: A Distributed Machine-learning System.
* [2013](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/02/shark_sigmod2013.pdf) - **AMPLab** - Shark: SQL and Rich Analytics at Scale.
* [2013](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/05/grades-graphx_with_fonts.pdf) - **AMPLab** - GraphX: A Resilient Distributed Graph System on Spark.
* [2013](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/40671.pdf) - **Google** - HyperLogLog in Practice: Algorithmic Engineering of a State of The Art Cardinality Estimation Algorithm.
* [2013](http://research.microsoft.com/pubs/200169/now-vldb.pdf) - **Microsoft** - Scalable Progressive Analytics on Big Data in the Cloud.
* [2013](http://static.druid.io/docs/druid.pdf) - **Metamarkets** - Druid: A Real-time Analytical Data Store.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p764-rae.pdf) - **Google** - Online, Asynchronous Schema Change in F1.
* [2013](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/41344.pdf) - **Google** - F1: A Distributed SQL Database That Scales.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p734-akidau.pdf) - **Google** - MillWheel: Fault-Tolerant Stream Processing at Internet Scale.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p767-wiener.pdf) - **Facebook** - Scuba: Diving into Data at Facebook.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p871-curtiss.pdf) - **Facebook** - Unicorn: A System for Searching the Social Graph.
* [2013](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) - **Facebook** - Scaling Memcache at Facebook.

### 2011 - 2012

* [2012](http://vldb.org/pvldb/vol5/p1771_georgelee_vldb2012.pdf) - **Twitter** - The Unified Logging Infrastructure
  for Data Analytics at Twitter.
* [2012](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/04/blinkdb_vldb12_demo.pdf) - **AMPLab** - Blink and It’s Done: Interactive Queries on Very Large Data.
* [2012](https://www.usenix.org/system/files/login/articles/zaharia.pdf) - **AMPLab** - Fast and Interactive Analytics over Hadoop Data with Spark.
* [2012](https://amplab.cs.berkeley.edu/wp-content/uploads/2012/03/mod482-xin1.pdf) - **AMPLab** - Shark: Fast Data Analysis Using Coarse-grained Distributed Memory.
* [2012](https://www.usenix.org/legacy/event/nsdi11/tech/full_papers/Bolosky.pdf) - **Microsoft** - Paxos Replicated State Machines as the Basis of a High-Performance Data Store.
* [2012](http://research.microsoft.com/pubs/178045/ppaoxs-paper29.pdf) - **Microsoft** - Paxos Made Parallel.
* [2012](https://arxiv.org/pdf/1203.5485.pdf) - **AMPLab** - BlinkDB: Queries with Bounded Errors and Bounded Response Times on Very Large Data.
* [2012](http://vldb.org/pvldb/vol5/p1436_alexanderhall_vldb2012.pdf) - **Google** - Processing a trillion cells per mouse click.
* [2012](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) - **Google** - Spanner: Google’s Globally-Distributed Database.
* [2011](https://amplab.cs.berkeley.edu/wp-content/uploads/2011/06/euro118-ananthanarayanan.pdf) - **AMPLab** - Scarlett: Coping with Skewed Popularity Content in MapReduce Clusters.
* [2011](https://amplab.cs.berkeley.edu/wp-content/uploads/2011/06/Mesos-A-Platform-for-Fine-Grained-Resource-Sharing-in-the-Data-Center.pdf) - **AMPLab** - Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center.
* [2011](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36971.pdf) - **Google** - Megastore: Providing Scalable, Highly Available Storage for Interactive Services.

### 2001 - 2010

* [2010](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf) - **Facebook** - Finding a needle in Haystack: Facebook’s photo storage.
* [2010](https://amplab.cs.berkeley.edu/wp-content/uploads/2011/06/Spark-Cluster-Computing-with-Working-Sets.pdf) - **AMPLab** - Spark: Cluster Computing with Working Sets.
* [2010](http://kowshik.github.io/JPregel/pregel_paper.pdf) - **Google** - Pregel: A System for Large-Scale Graph Processing.
* [2010](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36726.pdf) - **Google** - Large-scale Incremental Processing Using Distributed Transactions and notifications base of Percolator and Caffeine.
* [2010](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf) - **Google** - Dremel: Interactive Analysis of Web-Scale Datasets.
* [2010](http://leoneu.github.io/) - **Yahoo** - S4: Distributed Stream Computing Platform.
* [2009](http://www.cs.umd.edu/~abadi/papers/hadoopdb.pdf) - HadoopDB: An Architectural Hybrid of MapReduce and DBMS Technologies for Analytical Workloads.
* [2008](https://cwiki.apache.org/confluence/download/attachments/120729877/chukwa_cca08.pdf?version=1\&modificationDate=1562667399000\&api=v2) - **AMPLab** - Chukwa: A large-scale monitoring system.
* [2007](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf) - **Amazon** - Dynamo: Amazon’s Highly Available Key-value Store.
* [2006](http://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf) - **Google** - The Chubby lock service for loosely-coupled distributed systems.
* [2006](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en//archive/bigtable-osdi06.pdf) - **Google** - Bigtable: A Distributed Storage System for Structured Data.
* [2004](http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) - **Google** - MapReduce: Simplied Data Processing on Large Clusters.
* [2003](http://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) - **Google** - The Google File System.

## Videos

* [Spark in Motion](https://www.manning.com/livevideo/spark-in-motion) - Spark in Motion teaches you how to use Spark for batch and streaming data analytics.
* [Machine Learning, Data Science and Deep Learning with Python ](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python) - LiveVideo tutorial that covers machine learning, Tensorflow, artificial intelligence, and neural networks.
* [Data warehouse schema design - dimensional modeling and star schema](https://snir.dev/talks/data-warehouse-schema-design) - Introduction to schema design for data warehouse using the star schema method.
* [Elasticsearch 7 and Elastic Stack](https://www.manning.com/livevideo/elasticsearch-7-and-elastic-stack) - LiveVideo tutorial that covers searching, analyzing, and visualizing big data on a cluster with Elasticsearch, Logstash, Beats, Kibana, and more.

## Books

#### Streaming

* [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-at-scale-with-python-and-dask) - Data Science at Scale with Python and Dask teaches you how to build distributed data projects that can handle huge amounts of data.
* [Streaming Data](https://www.manning.com/books/streaming-data) - Streaming Data introduces the concepts and requirements of streaming and real-time data systems.
* [Storm Applied](https://www.manning.com/books/storm-applied) - Storm Applied is a practical guide to using Apache Storm for the real-world tasks associated with processing and analyzing real-time data streams.
* [Fundamentals of Stream Processing: Application Design, Systems, and Analytics](http://www.cambridge.org/us/academic/subjects/engineering/communications-and-signal-processing/fundamentals-stream-processing-application-design-systems-and-analytics) - This comprehensive, hands-on guide combining the fundamental building blocks and emerging research in stream processing is ideal for application designers, system builders, analytic developers, as well as students and researchers in the field.
* [Stream Data Processing: A Quality of Service Perspective](http://www.springer.com/us/book/9780387710020) - Presents a new paradigm suitable for stream and complex event processing.
* [Unified Log Processing](https://www.manning.com/books/event-streams-in-action) - Unified Log Processing is a practical guide to implementing a unified log of event streams (Kafka or Kinesis) in your business
* [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action) - Kafka Streams in Action teaches you everything you need to know to implement stream processing on data flowing into your Kafka platform, allowing you to focus on getting more from your data without sacrificing time or effort.
* [Big Data](https://www.manning.com/books/big-data) - Big Data teaches you to build big data systems using an architecture that takes advantage of clustered hardware along with new tools designed specifically to capture and analyze web-scale data.
* [Spark in Action](https://www.manning.com/books/spark-in-action) & [Spark in Action 2nd Ed.](https://www.manning.com/books/spark-in-action-second-edition) - Spark in Action teaches you the theory and skills you need to effectively handle batch and streaming data using Spark. Fully updated for Spark 2.0.
* [Kafka in Action](https://www.manning.com/books/kafka-in-action) - Kafka in Action is a fast-paced introduction to every aspect of working with Kafka you need to really reap its benefits.
* [Fusion in Action](https://www.manning.com/books/fusion-in-action-cx) - Fusion in Action teaches you to build a full-featured data analytics pipeline, including document and data search and distributed data clustering.
* [Reactive Data Handling](https://www.manning.com/books/reactive-data-handling) - Reactive Data Handling is a collection of five hand-picked chapters, selected by Manuel Bernhardt, that introduce you to building reactive applications capable of handling real-time processing with large data loads--free eBook!
* [Azure Data Engineering](https://www.manning.com/books/azure-data-engineering) - A book about data engineering in general and the Azure platform specifically
* [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) - Grokking Streaming Systems helps you unravel what streaming systems are, how they work, and whether they’re right for your business. Written to be tool-agnostic, you’ll be able to apply what you learn no matter which framework you choose.
* [Data Analysis with Python and PySpark](https://www.manning.com/books/data-analysis-with-python-and-pyspark) - tutorial for using PySpark to build data-driven applications at scale.
* [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) - practical guide to building and maintaining data pipelines with Airflow.

#### Distributed systems

* [Distributed Systems for fun and profit](http://book.mixu.net/distsys/) – Theory of distributed systems. Include parts about time and ordering, replication and impossibility results.

#### Graph Based approach

* [Graph-Powered Machine Learning](https://www.manning.com/books/graph-powered-machine-learning) - Alessandro Negro. Combine graph theory and models to improve machine learning projects

### Data Visualization

* [The beauty of data visualization](https://www.youtube.com/watch?v=5Zg-C8AAIGg)
* [Designing Data Visualizations with Noah Iliinsky](https://www.youtube.com/watch?v=R-oiKt7bUU8)
* [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo)
* [Ice Bucket Challenge Data Visualization](https://www.youtube.com/watch?v=qTEchen97rQ)

# Other Awesome Lists

* Even more lists [awesome](https://github.com/sindresorhus/awesome) ⭐ 498,094 | 🐛 105 | 📅 2026-08-18.
* Public Datasets [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) ⭐ 78,226 | 🐛 159 | 📅 2026-08-04.
* Other awesome lists [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,611 | 🐛 60 | 🌐 Ruby | 📅 2024-06-02.
* Another list? [list](https://github.com/jnv/lists) ⭐ 11,425 | 🐛 21 | 📅 2026-03-23.
* Graph Classification [awesome-graph-classification](https://github.com/benedekrozemberczki/awesome-graph-classification) ⭐ 4,799 | 🐛 0 | 🌐 Python | 📅 2023-03-18.
* Analytics [awesome-analytics](https://github.com/onurakpolat/awesome-analytics) ⭐ 4,302 | 🐛 56 | 📅 2026-02-17.
* Network Embedding [awesome-network-embedding](https://github.com/chihming/awesome-network-embedding) ⭐ 2,627 | 🐛 4 | 📅 2020-12-08.
* Decision Tree Papers [awesome-decision-tree-papers](https://github.com/benedekrozemberczki/awesome-decision-tree-papers) ⭐ 2,473 | 🐛 3 | 🌐 Python | 📅 2025-12-28.
* Community Detection [awesome-community-detection](https://github.com/benedekrozemberczki/awesome-community-detection) ⭐ 2,449 | 🐛 0 | 🌐 Python | 📅 2025-12-20.
* WTF! [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome) ⭐ 2,238 | 🐛 5 | 📅 2023-11-13.
* Fraud Detection Papers [awesome-fraud-detection-papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers) ⭐ 1,825 | 🐛 2 | 🌐 Python | 📅 2026-01-05.
* Gradient Boosting Papers [awesome-gradient-boosting-papers](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers) ⭐ 1,049 | 🐛 3 | 🌐 Python | 📅 2026-01-05.
* Data Annotation and Labeling Tools [awesome-open-data-annotation](https://github.com/zenml-io/awesome-open-data-annotation) ⭐ 723 | 🐛 2 | 📅 2026-07-06.
* Monte Carlo Tree Search Papers [awesome-monte-carlo-tree-search-papers](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers) ⭐ 713 | 🐛 0 | 🌐 Python | 📅 2026-01-13.
* Kafka [awesome-kafka](https://github.com/monksy/awesome-kafka) ⭐ 216 | 🐛 1 | 📅 2026-05-13.
* [Google Bigtable](https://github.com/zrosenbauer/awesome-bigtable) ⭐ 56 | 🐛 1 | 📅 2022-09-19.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
