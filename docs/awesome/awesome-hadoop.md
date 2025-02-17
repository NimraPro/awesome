<div class="github-widget" data-repo="youngwookim/awesome-hadoop"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Hadoop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome Hadoop and Hadoop ecosystem resources. Inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php), [Awesome Python](https://github.com/vinta/awesome-python) and [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin)


## Hadoop

* [Apache Hadoop](http://hadoop.apache.org/) - Apache Hadoop
* [Apache Hadoop Ozone](http://hadoop.apache.org/ozone/) - An Object Store for Apache Hadoop
* [Apache Tez](http://tez.apache.org/) - A Framework for YARN-based, Data Processing Applications In Hadoop
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) - SpatialHadoop is a MapReduce extension to Apache Hadoop designed specially to work with spatial data. 
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) - Big Data Spatial Analytics for the Hadoop Framework
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop. Supports Map/Reduce, Cascading, Apache Hive and Apache Pig.
* [hadoopy](https://github.com/bwhite/hadoopy) - Python MapReduce library written in Cython. 
* [mrjob](https://github.com/Yelp/mrjob/) - mrjob is a Python 2.5+ package that helps you write and run Hadoop Streaming jobs.
* [pydoop](http://pydoop.sourceforge.net/) - Pydoop is a package that provides a Python API for Hadoop.
* [hdfs-du](https://github.com/twitter/hdfs-du) - HDFS-DU is an interactive visualization of the Hadoop distributed file system. 
* [White Elephant](https://github.com/linkedin/white-elephant) - Hadoop log aggregator and dashboard
* [Genie](https://github.com/Netflix/genie) - Genie provides REST-ful APIs to run Hadoop, Hive and Pig jobs, and to manage multiple Hadoop resources and perform job submissions across them.
* [Apache Kylin](http://kylin.incubator.apache.org/) - Apache Kylin is an open source Distributed Analytics Engine from eBay Inc. that provides SQL interface and multi-dimensional analysis (OLAP) on Hadoop supporting extremely large datasets
* [Crunch](https://github.com/jondot/crunch) - Go-based toolkit for ETL and feature extraction on Hadoop
* [Apache Ignite](http://ignite.apache.org/) - Distributed in-memory platform

## YARN

* [Apache Slider](http://slider.incubator.apache.org/) - Apache Slider is a project in incubation at the Apache Software Foundation with the goal of making it possible and easy to deploy existing applications onto a YARN cluster.
* [Apache Twill](http://twill.incubator.apache.org/) - Apache Twill is an abstraction over Apache Hadoop® YARN that reduces the complexity of developing distributed applications, allowing developers to focus more on their application logic.
* [mpich2-yarn](https://github.com/alibaba/mpich2-yarn) - Running MPICH2 on Yarn

## NoSQL
*Next Generation Databases mostly addressing some of the points: being non-relational, distributed, open-source and horizontally scalable.*

* [Apache HBase](http://hbase.apache.org) - Apache HBase
* [Apache Phoenix](http://phoenix.apache.org/) - A SQL skin over HBase supporting secondary indices
* [happybase](https://github.com/wbolster/happybase) - A developer-friendly Python library to interact with Apache HBase.
* [Hannibal](https://github.com/sentric/hannibal) - Hannibal is tool to help monitor and maintain HBase-Clusters that are configured for manual splitting.
* [Haeinsa](https://github.com/VCNC/haeinsa) - Haeinsa is linearly scalable multi-row, multi-table transaction library for HBase
* [hindex](https://github.com/Huawei-Hadoop/hindex) - Secondary Index for HBase
* [Apache Accumulo](https://accumulo.apache.org/) - The Apache Accumulo™ sorted, distributed key/value store is a robust, scalable, high performance data storage and retrieval system.
* [OpenTSDB](http://opentsdb.net/) - The Scalable Time Series Database
* [Apache Cassandra](http://cassandra.apache.org/)

## SQL on Hadoop
*SQL on Hadoop*

* [Apache Hive](http://hive.apache.org) - The Apache Hive data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL
* [Apache Phoenix](http://phoenix.apache.org) A SQL skin over HBase supporting secondary indices
* [Apache HAWQ (incubating)](http://hawq.incubator.apache.org/) - Apache HAWQ is a Hadoop native SQL query engine that combines the key technological advantages of MPP database with the scalability and convenience of Hadoop
* [Lingual](http://www.cascading.org/projects/lingual/) - SQL interface for Cascading (MR/Tez job generator)
* [Apache Impala](https://impala.apache.org/) - Apache Impala is an open source massively parallel processing (MPP) SQL query engine for data stored in a computer cluster running Apache Hadoop. Impala has been described as the open-source equivalent of Google F1, which inspired its development in 2012.
* [Presto](https://prestodb.io/) - Distributed SQL Query Engine for Big Data. Open sourced by Facebook.
* [Apache Tajo](http://tajo.apache.org/) - Data warehouse system for Apache Hadoop
* [Apache Drill](https://drill.apache.org/) - Schema-free SQL Query Engine
* [Apache Trafodion](http://trafodion.apache.org/)

## Data Management

* [Apache Calcite](http://calcite.apache.org/) - A Dynamic Data Management Framework
* [Apache Atlas](http://atlas.incubator.apache.org/) - Metadata tagging & lineage capture suppoting complex business data taxonomies
* [Apache Kudu](https://kudu.apache.org/) - Kudu provides a combination of fast inserts/updates and efficient columnar scans to enable multiple real-time analytic workloads across a single storage layer, complementing HDFS and Apache HBase.
* [Confluent Schema registry for Kafka](https://github.com/confluentinc/schema-registry) - Schema Registry provides a serving layer for your metadata. It provides a RESTful interface for storing and retrieving Avro schemas.
* [Hortonworks Schema Registry](https://github.com/hortonworks/registry) - Schema Registry is a framework to build metadata repositories.

## Workflow, Lifecycle and Governance

* [Apache Oozie](http://oozie.apache.org) - Apache Oozie
* [Azkaban](http://azkaban.github.io/)
* [Apache Falcon](http://falcon.apache.org/) - Data management and processing platform
* [Apache NiFi](http://nifi.apache.org/) - A dataflow system
* [Apache AirFlow](https://github.com/apache/incubator-airflow) - Airflow is a workflow automation and scheduling system that can be used to author and manage data pipelines
* [Luigi](http://luigi.readthedocs.org/en/latest/) - Python package that helps you build complex pipelines of batch jobs

## Data Ingestion and Integration

* [Apache Flume](http://flume.apache.org) - Apache Flume
* [Suro](https://github.com/Netflix/suro) - Netflix's distributed Data Pipeline
* [Apache Sqoop](http://sqoop.apache.org) - Apache Sqoop
* [Apache Kafka](http://kafka.apache.org/) - Apache Kafka
* [Gobblin from LinkedIn](https://github.com/linkedin/gobblin) - Universal data ingestion framework for Hadoop

## DSL

* [Apache Pig](http://pig.apache.org) - Apache Pig
* [Apache DataFu](http://datafu.incubator.apache.org/) - A collection of libraries for working with large-scale data in Hadoop
* [vahara](https://github.com/thedatachef/varaha) - Machine learning and natural language processing with Apache Pig
* [packetpig](https://github.com/packetloop/packetpig) - Open Source Big Data Security Analytics
* [akela](https://github.com/mozilla-metrics/akela) - Mozilla's utility library for Hadoop, HBase, Pig, etc.
* [seqpig](http://seqpig.sourceforge.net/) - Simple and scalable scripting for large sequencing data set(ex: bioinfomation) in Hadoop 
* [Lipstick](https://github.com/Netflix/Lipstick) - Pig workflow visualization tool. [Introducing Lipstick on A(pache) Pig](http://techblog.netflix.com/2013/06/introducing-lipstick-on-apache-pig.html)
* [PigPen](https://github.com/Netflix/PigPen) - PigPen is map-reduce for Clojure, or distributed Clojure. It compiles to Apache Pig, but you don't need to know much about Pig to use it.

## Libraries and Tools

* [Kite Software Development Kit](http://kitesdk.org/) - A set of libraries, tools, examples, and documentation
* [gohadoop](https://github.com/hortonworks/gohadoop) - Native go clients for Apache Hadoop YARN.
* [Hue](http://gethue.com/) - A Web interface for analyzing data with Apache Hadoop.
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) - A web-based notebook that enables interactive data analytics
* [Apache Thrift](http://thrift.apache.org/)
* [Apache Avro](http://avro.apache.org/) - Apache Avro is a data serialization system.
* [Elephant Bird](https://github.com/twitter/elephant-bird) - Twitter's collection of LZO and Protocol Buffer-related Hadoop, Pig, Hive, and HBase code.
* [Spring for Apache Hadoop](http://projects.spring.io/spring-hadoop/)
* [hdfs - A native go client for HDFS](https://github.com/colinmarc/hdfs)
* [snakebite](https://pypi.python.org/pypi/snakebite/) - A pure python HDFS client
* [Apache Parquet](https://parquet.apache.org/) - Apache Parquet is a columnar storage format available to any project in the Hadoop ecosystem, regardless of the choice of data processing framework, data model or programming language.
* [Apache Superset (incubating)](https://superset.incubator.apache.org/) - Apache Superset (incubating) is a modern, enterprise-ready business intelligence web application
* [Schema Registry UI](https://github.com/Landoop/schema-registry-ui) - Web tool for the Confluent Schema Registry in order to create / view / search / evolve / view history & configure Avro schemas of your Kafka cluster.

## Realtime Data Processing

* [Apache Storm](http://storm.apache.org/)
* [Apache Samza](http://samza.apache.org/)
* [Apache Spark](http://spark.apache.org/streaming/)
* [Apache Flink](https://flink.apache.org) - Apache Flink is a platform for efficient, distributed, general-purpose data processing. It supports exactly once stream processing.
* [Apache Pulsar (incubating)](http://pulsar.incubator.apache.org/) - Apache Pulsar (incubating) is a highly scalable, low latency messaging platform running on commodity hardware. It provides simple pub-sub semantics over topics, guaranteed at-least-once delivery of messages, automatic cursor management for subscribers, and cross-datacenter replication.
* [Apache Druid (incubating)](http://druid.incubator.apache.org/) - A high-performance, column-oriented, distributed data store.

## Distributed Computing and Programming

* [Apache Spark](http://spark.apache.org/)
 * [Spark Packages](http://spark-packages.org/) - A community index of packages for Apache Spark
 * [SparkHub](https://sparkhub.databricks.com/) - A community site for Apache Spark
* [Apache Crunch](http://crunch.apache.org)
* [Cascading](http://www.cascading.org/) - Cascading is the proven application development platform for building data applications on Hadoop.
* [Apache Flink](http://flink.apache.org/) - Apache Flink is a platform for efficient, distributed, general-purpose data processing.
* [Apache Apex (incubating)](http://apex.incubator.apache.org/) - Enterprise-grade unified stream and batch processing engine.
* [Apache Livy (incubating)](https://livy.incubator.apache.org/) - Apache Livy (incubating) is web service that exposes a REST interface for managing long running Apache Spark contexts in your cluster. With Livy, new applications can be built on top of Apache Spark that require fine grained interaction with many Spark contexts.

## Packaging, Provisioning and Monitoring

* [Apache Bigtop](http://bigtop.apache.org/) - Apache Bigtop: Packaging and tests of the Apache Hadoop ecosystem 
* [Apache Ambari](http://ambari.apache.org/) - Apache Ambari
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/)
* [ankush](https://github.com/impetus-opensource/ankush) - A big data cluster management tool that creates and manages clusters of different technologies.
* [Apache Zookeeper](http://zookeeper.apache.org/) - Apache Zookeeper
* [Apache Curator](http://curator.apache.org/) - ZooKeeper client wrapper and rich ZooKeeper framework
* [inviso](https://github.com/Netflix/inviso) - Inviso is a lightweight tool that provides the ability to search for Hadoop jobs, visualize the performance, and view cluster utilization.
* [Logit.io](https://logit.io/) - Send logs from Hadoop to Elasticsearch for monitoring and alerting.


## Search

* [ElasticSearch](https://www.elastic.co/)
* [Apache Solr](http://lucene.apache.org/solr/) - Apache Solr is an open source search platform built upon a Java library called Lucene.
* [Banana](https://github.com/LucidWorks/banana) - Kibana port for Apache Solr

## Search Engine Framework

* [Apache Nutch](http://nutch.apache.org/) - Apache Nutch is a highly extensible and scalable open source web crawler software project.

## Security

* [Apache Ranger](http://ranger.incubator.apache.org/) - Ranger is a framework to enable, monitor and manage comprehensive data security across the Hadoop platform.
* [Apache Sentry](https://sentry.incubator.apache.org/) - An authorization module for Hadoop
* [Apache Knox Gateway](https://knox.apache.org/) - A REST API Gateway for interacting with Hadoop clusters.

## Benchmark

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)
* [HiBench](https://github.com/intel-hadoop/HiBench)
* [YCSB](https://github.com/brianfrankcooper/YCSB) - The Yahoo! Cloud Serving Benchmark (YCSB) is an open-source specification and program suite for evaluating retrieval and maintenance capabilities of computer programs. It is often used to compare relative performance of NoSQL database management systems.

## Machine learning and Big Data analytics

* [Apache Mahout](http://mahout.apache.org)
* [Oryx 2](https://github.com/OryxProject/oryx) - Lambda architecture on Spark, Kafka for real-time large scale machine learning
* [MLlib](https://spark.apache.org/mllib/) - MLlib is Apache Spark's scalable machine learning library.
* [R](http://www.r-project.org/) - R is a free software environment for statistical computing and graphics.
* [RHadoop](https://github.com/RevolutionAnalytics/RHadoop/wiki) including RHDFS, RHBase, RMR2, plyrmr
* [Apache Lens](http://lens.apache.org/)
* [Apache SINGA (incubating)](https://singa.incubator.apache.org/) - SINGA is a general distributed deep learning platform for training big deep learning models over large datasets
* [BigDL](https://bigdl-project.github.io/) - BigDL is a distributed deep learning library for Apache Spark; with BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.
* [Apache Hivemall (incubating)](http://hivemall.incubator.apache.org/) - Apache Hivemall is a scalable machine learning library that runs on Apache Hive, Spark and Pig.

## Misc.

* Hive Plugins
 * UDF
     * https://github.com/edwardcapriolo/hive_cassandra_udfs
     * https://github.com/livingsocial/HiveSwarm
     * https://github.com/ThinkBigAnalytics/Hive-Extensions-from-Think-Big-Analytics
     * https://github.com/twitter/elephant-bird - Twitter
     * https://github.com/lovelysystems/ls-hive
     * https://github.com/klout/brickhouse
 * Storage Handler
     * https://github.com/dvasilen/Hive-Cassandra
     * https://github.com/yc-huang/Hive-mongo
     * https://github.com/balshor/gdata-storagehandler
     * https://github.com/chimpler/hive-solr
     * https://github.com/bfemiano/accumulo-hive-storage-manager
 * Libraries and tools
     * https://github.com/forward3d/rbhive
     * https://github.com/synctree/activerecord-hive-adapter
     * https://github.com/hrp/sequel-hive-adapter
     * https://github.com/forward/node-hive
     * https://github.com/recruitcojp/WebHive
     * [shib](https://github.com/tagomoris/shib) - WebUI for query engines: Hive and Presto
     * https://github.com/dmorel/Thrift-API-HiveClient2 (Perl - HiveServer2)
     * [PyHive](https://github.com/dropbox/PyHive) - Python interface to Hive and Presto
     * https://github.com/recruitcojp/OdbcHive
     * [HiveRunner](https://github.com/klarna/HiveRunner) - An Open Source unit test framework for hadoop hive queries based on JUnit4
     * [Beetest](https://github.com/kawaa/Beetest) - A super simple utility for testing Apache Hive scripts locally for non-Java developers.
     * [Hive_test](https://github.com/edwardcapriolo/hive_test)- Unit test framework for hive and hive-service
* Flume Plugins
  * [Flume MongoDB Sink](https://github.com/leonlee/flume-ng-mongodb-sink)
  * [Flume RabbitMQ source and sink](https://github.com/jcustenborder/flume-ng-rabbitmq)
  * [Flume UDP Source](https://github.com/whitepages/flume-udp-source)
  * [.Net FlumeNG Clients](https://github.com/marksl/DotNetFlumeNG.Clients)

## Resources
Various resources, such as books, websites and articles.

## Websites
*Useful websites and articles*

* [Hadoop Weekly](http://www.hadoopweekly.com/)
* [The Hadoop Ecosystem Table](http://hadoopecosystemtable.github.io/)
* [Hadoop illuminated](http://hadoopilluminated.com/) - Open Source Hadoop Book
* [AWS BigData Blog](http://blogs.aws.amazon.com/bigdata/)
* [Hadoop360](http://www.hadoop360.com/)
* [How to monitor Hadoop metrics](https://www.datadoghq.com/blog/monitor-hadoop-metrics/)

## Presentations

* [Apache Hadoop In Theory And Practice](http://www.slideshare.net/AdamKawa/hadoop-intheoryandpractice)
* [Hadoop Operations at LinkedIn](http://www.slideshare.net/allenwittenauer/2013-hadoopsummitemea)
* [Hadoop Performance at LinkedIn](http://www.slideshare.net/allenwittenauer/2012-lihadoopperf)
* [Docker based Hadoop provisioning](http://www.slideshare.net/JanosMatyas/docker-based-hadoop-provisioning)

## Books

* [Hadoop: The Definitive Guide](http://www.amazon.com/gp/product/1449311520/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449311520&linkCode=as2&tag=matratsblo-20)
* [Hadoop Operations](http://www.amazon.com/gp/product/1449327052/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449327052&linkCode=as2&tag=matratsblo-20)
* [Apache Hadoop Yarn](http://www.amazon.com/dp/0321934504?tag=matratsblo-20)
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do)
* [Programming Pig](http://shop.oreilly.com/product/0636920018087.do)
* [Programming Hive](http://shop.oreilly.com/product/0636920023555.do)
* [Hadoop in Practice, Second Edition](http://www.manning.com/holmes2/)
* [Hadoop in Action, Second Edition](http://www.manning.com/lam2/)

## Hadoop and Big Data Events
* [ApacheCon](http://www.apachecon.com/)
* [Strata + Hadoop World](http://conferences.oreilly.com/strata)
* [DataWorks Summit](https://dataworkssummit.com/)
* [Spark Summit](https://databricks.com/sparkaisummit)

## Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) and [awesome](https://github.com/sindresorhus/awesome) list.