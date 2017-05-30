<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="akullpp/awesome-java">akullpp/awesome-java</a> with ranks
</p>
---
# Awesome Java [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A curated list of awesome Java frameworks, libraries and software.

- [Awesome Java](#awesome-java)
    - [Ancients](#ancients)
    - [Bean Mapping](#bean-mapping)
    - [Build](#build)
    - [Bytecode Manipulation](#bytecode-manipulation)
    - [Caching](#caching)
    - [Cluster Management](#cluster-management)
    - [Code Analysis](#code-analysis)
    - [Code Coverage](#code-coverage)
    - [Code Generators](#code-generators)
    - [Command-line Argument Parsers](#command-line-argument-parsers)
    - [Compiler-compiler](#compiler-compiler)
    - [Configuration](#configuration)
    - [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
    - [CSV](#csv)
    - [Data structures](#data-structures)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Dependency Injection](#dependency-injection)
    - [Development](#development)
    - [Distributed Applications](#distributed-applications)
    - [Distributed Databases](#distributed-databases)
    - [Distribution](#distribution)
    - [Document Processing](#document-processing)
    - [Formal Verification](#formal-verification)
    - [Functional Programming](#functional-programming)
    - [Game Development](#game-development)
    - [Geospatial](#geospatial)
    - [GUI](#gui)
    - [High Performance](#high-performance)
    - [HTTP Clients](#http-clients)
    - [Hypermedia Types](#hypermedia-types)
    - [IDE](#ide)
    - [Imagery](#imagery)
    - [JSON Processing](#json-processing)
    - [JSON](#json)
    - [JVM and JDK](#jvm-and-jdk)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microservice](#microservice)
    - [Miscellaneous](#miscellaneous)
    - [Monitoring](#monitoring)
    - [Native](#native)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [ORM](#orm)
    - [PaaS](#paas)
    - [PDF](#pdf)
    - [Performance analysis](#performance-analysis)
    - [Platform](#platform)
    - [Reactive libraries](#reactive-libraries)
    - [REST Frameworks](#rest-frameworks)
    - [Science](#science)
    - [Search](#search)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server](#server)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Utility](#utility)
    - [Version Managers](#version-managers)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
- [Resources](#resources)
    - [Awesome Lists](#awesome-lists)
    - [Communities](#communities)
    - [Frontends](#frontends)
    - [Influential Books](#influential-books)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
- [Contributing](#contributing)

## Ancients

*In existence since the beginning of time and which will continue being used long after the hype has waned.*

* [Apache Ant](http://ant.apache.org/) - Build process management with XML.
* [Apache Hadoop](http://hadoop.apache.org/) - Storage and large-scale processing of data-sets on clusters of commodity hardware.
* [Apache OpenNLP](https://opennlp.apache.org/) - Toolkit for common tasks like tokenization.
* [Apache Velocity](http://velocity.apache.org/) - Templates for HTML pages, emails or source code generation in general.
* [FreeMarker](http://freemarker.org/) - General templating engine with no heavyweight or opinionated dependencies.
* [GlassFish](https://glassfish.java.net/) - Application server and reference implementation for Java EE, sponsored by Oracle.
* [GWT](http://www.gwtproject.org/) - Toolbox that includes a Java-to-JavaScript compiler for client-side code, XML parser, API for RPC, JUnit integration, internationalization support and widgets for the GUI.
* [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Matchers that can be combined to create flexible expressions of intent.
* [HornetQ](http://hornetq.jboss.org/) - Clear, concise, modular and made to be embedded.
* [Hudson](http://hudson-ci.org/) - Continuous integration server still in active development.
* [Java Modeling Language (JML)](http://www.eecs.ucf.edu/~leavens/JML/) - Behavioral interface specification language useful for specifying the behavior of code modules. It combines Eiffel's Design by Contract approach with the model-based specification approach of the Larch family of interface specification languages, with some elements of the refinement calculus. Used by several other verification tools.
* [JavaCC](https://javacc.org/) - Parser generator with syntactic lookahead.
* [JavaServer Faces](https://javaserverfaces.java.net/) - Oracle's open-source implementation of the JSF standard, Mojarra.
* [JavaServer Pages](https://jsp.java.net/) - Common templating for websites with custom tag libraries.
* [JUnit](http://junit.org/) - Common testing framework.
* [Launch4j](http://launch4j.sourceforge.net/) - Wraps JARs in lightweight and native Windows executables.
* [Quartz ★842](quartz-scheduler/quartz) - Open-source job scheduler library with Apache 2.0 license.
* [TestNG](http://testng.org/) - Testing framework.
* [Trove](http://trove.starlight-systems.com/) - Primitive collections.

## Bean Mapping

*Frameworks that ease bean mapping.*

* [Dozer ★839](DozerMapper/dozer) - Mapper that copies data from one object to another, using annotations, API or XML configuration.
* [JMapper](http://jmapper-framework.github.io/jmapper-core/) - Using byte code manipulation for lightning fast mapping. Supporting annotations, API or XML configuration.
* [MapStruct ★712](mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention over configuration approach.
* [ModelMapper](https://github.com/jhalterman/modelmapper) - Intelligent object mapping library that automatically maps objects to each other.
* [Orika ★388](orika-mapper/orika) - Java Bean mapping framework that recursively copies (among other capabilities) data from one object to another.
* [Selma ★103](xebia-france/selma) - Annotation processor-based bean mapper.

## Build

*Tools that handle the build cycle and dependencies of an application.*

* [Apache Maven](http://maven.apache.org/) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
* [Bazel](http://bazel.io) - Tool from Google that builds code quickly and reliably.
* [Gradle](http://gradle.org/) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

## Bytecode Manipulation

*Libraries to manipulate bytecode programmatically.*

* [ASM](http://asm.ow2.org/) - All-purpose, low-level bytecode manipulation and analysis.
* [Byte Buddy](http://bytebuddy.net/) - Further simplifies bytecode generation with a fluent API.
* [Byteman](http://byteman.jboss.org/) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting.
* [cglib ★1321](cglib/cglib) - Bytecode generation library.
* [Javassist](http://jboss-javassist.github.io/javassist/) - Tries to simplify bytecode editing.

## Caching

*Libraries that provide caching facilities.*

* [Caffeine ★2601](ben-manes/caffeine) - High-performance, near-optimal caching library.
* [Ehcache](http://www.ehcache.org/) - Distributed general-purpose cache.

## Cluster Management

*Frameworks that can dynamically manage applications inside of a cluster.*

* [Apache Aurora](http://aurora.apache.org/) - Mesos framework for long-running services and cron jobs.
* [Apache Mesos](http://mesos.apache.org/) - Abstracts CPU, memory, storage, and other compute resources away from machines.
* [Singularity](http://getsingularity.com/) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

## Code Analysis

*Tools that provide metrics and quality measurements.*

* [Checkstyle ★2005](checkstyle/checkstyle) - Static analysis of coding conventions and standards.
* [Error Prone ★2626](google/error-prone) - Catches common programming mistakes as compile-time errors.
* [FindBugs](http://findbugs.sourceforge.net/) - Static analysis of bytecode to find potential bugs.
* [jQAssistant](http://jqassistant.org/) - Static code analysis with Neo4J-based query language.
* [PMD ★956](pmd/pmd) - Source code analysis for finding bad coding practices.
* [Spoon ★345](INRIA/spoon) - Library for analyzing and transforming Java source code.

## Code Coverage

*Frameworks and tools that enable code coverage metrics collection for test suites.*

* [Clover ![c]](https://www.atlassian.com/software/clover/overview) - Relies on source-code instrumentation instead of bytecode instrumentation.
* [Cobertura](http://cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics.
* [JaCoCo](http://eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

## Code Generators

*Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness.*

* [ADT4J ★94](sviperll/adt4j) - JSR-269 code generator for algebraic data types.
* [Auto ★5059](google/auto) - Generates factory, service, and value classes.
* [FreeBuilder ★597](google/FreeBuilder) - Automatically generates the Builder pattern.
* [Immutables](http://immutables.github.io/) - Annotation processors to generate simple, safe and consistent value objects.
* [JHipster ★7076](jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS.
* [Joda-Beans](http://www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
* [Lombok](https://projectlombok.org/) - Code generator that aims to reduce verbosity.

## Command-line Argument Parsers

*Libraries that make it easy to parse command line options, arguments, etc.*

* [picocli](http://picocli.info/) - ANSI colors and styles in usage help. Can be included as source to avoid dependency. Annotation based, POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.
* [Airline ★546](airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments.
* [args4j](http://args4j.kohsuke.org/) - Small library to parse command-line arguments.
* [JCommander](http://jcommander.org/) - Command-line argument parsing framework with custom types and validation via implementing interfaces.
* [JOpt Simple](http://pholser.github.io/jopt-simple/) - Simple parser that uses the POSIX getopt() and GNU getopt_long() syntaxes. Uses a fluent API instead of annotations.

## Compiler-compiler

*Frameworks that help to create parsers, interpreters or compilers.*

* [ANTLR](http://www.antlr.org/) - Complex full-featured framework for top-down parsing.
* [JFlex](http://jflex.de/) - A lexical analyzer generator.

## Configuration

*Libraries that provide external configuration.*

* [config ★2780](typesafehub/config) - Configuration library for JVM languages.
* [ini4j](http://ini4j.sourceforge.net/) - Provides an API for handling Windows' INI files.
* [KAConf ★12](mariomac/kaconf) - Annotation-based configuration system for Java and Kotlin.
* [owner ★503](lviggiano/owner) - Reduces boilerplate of properties.

## Constraint Satisfaction Problem Solver

*Libraries that help with implementing optimization and satisfiability problems.*

* [Choco](http://choco-solver.org/) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
* [JaCoP ★101](radsz/jacop) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models.
* [OptaPlanner](http://www.optaplanner.org/) - Business planning and resource scheduling optimization solver.

## CSV

*Frameworks and libraries that simplify reading/writing CSV data.*

* [jackson-dataformat-csv ★179](FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV.
* [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
* [Super CSV](http://super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
* [uniVocity-parsers ★351](uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed width records.

## Database

*Everything that simplifies interactions with the database.*

* [Apache Hive](https://hive.apache.org/) - Data warehouse infrastructure built on top of Hadoop.
* [Apache Phoenix](http://phoenix.apache.org/) - High-performance relational database layer over HBase for low-latency applications.
* [Chronicle Map ★986](OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.
* [eXist ★169](eXist-db/exist) - A NoSQL document database and application platform.
* [FlexyPool ★398](vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions.
* [Flyway](https://flywaydb.org/) - Simple database migration tool.
* [H2](http://h2database.com/) - Small SQL database notable for its in-memory functionality.
* [HikariCP ★4636](brettwooldridge/HikariCP) - High-performance JDBC connection pool.
* [JDBI](http://jdbi.org/) - Convenient abstraction of JDBC.
* [Jedis ★5163](xetorthio/jedis) - A small client for interaction with Redis, with methods for commands.
* [jetcd ★119](justinsb/jetcd) - A client library for etcd.
* [jOOQ](http://www.jooq.org/) - Generates typesafe code based on SQL schema.
* [Liquibase](http://www.liquibase.org/) - Database-independent library for tracking, managing and applying database schema changes.
* [MapDB](http://www.mapdb.org/) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
* [MariaDB4j ★149](vorburger/MariaDB4j) - Launcher for MariaDB that requires no installation or external dependencies.
* [Presto ★6053](prestodb/presto) - Distributed SQL query engine for big data.
* [Querydsl](http://www.querydsl.com/) - Typesafe unified queries.
* [Realm ★7782](realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables.
* [Redisson](https://github.com/mrniko/redisson) - Allows for distributed and scalable data structures on top of a Redis server.
* [requery ★1929](requery/requery) - A modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, perform queries and updates from any platform that uses Java.
* [Speedment ★959](speedment/speedment) - Database access library that utilizes the Java 8 Stream API for querying.
* [sql2o](http://sql2o.org/) - Thin JDBC wrapper that simplifies database access and provides simple mapping of ResultSets to POJOs.
* [Vibur DBCP](http://www.vibur.org/) - JDBC connection pool library with advanced performance monitoring capabilities.

## Data Structures

*Efficient and specific data structures.*

* [Apache Avro](https://avro.apache.org/) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
* [Apache Orc](https://orc.apache.org/) - Fast and efficient columnar storage format for Hadoop-based workloads.
* [Apache Parquet](http://parquet.apache.org/) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
* [Apache Thrift](https://thrift.apache.org/) - Data interchange format that originated at Facebook.
* [Big Queue ★242](bulldog2011/bigqueue) - A big, fast and persistent queue based on memory mapped file.
* [Persistent Collection](http://pcollections.org/) - Persistent and immutable analogue of the Java Collections Framework.
* [Protobuf ★17605](google/protobuf) - Google's data interchange format.
* [SBE ★1107](real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around.
* [Tape ★1843](square/tape) - A lightning fast, transactional, file-based FIFO.
* [Wire ★1997](square/wire) - Clean, lightweight protocol buffers.

## Date and Time

*Libraries related to handling date and time.*

* [Almanac Converter](https://github.com/hypotemoose/almanac-converter) - Simple conversion between different calendar systems.
* [iCal4j ★198](ical4j/ical4j) - Parsing and building iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models.
* [Joda-Time](http://www.joda.org/joda-time/) - De facto standard date/time-library before Java 8.
* [ThreeTenBP ★260](ThreeTen/threetenbp) - Port of JSR 310 (java.time package) by the author of Joda-Time.
* [Time4J ★131](MenoData/Time4J) - Advanced date and time library.

## Dependency Injection

*Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm.*

* [Apache DeltaSpike](https://deltaspike.apache.org/) - CDI extension framework.
* [Dagger2](http://google.github.io/dagger/) - Compile-time injection framework without reflection.
* [Feather ★221](zsoltherpai/feather) - Ultra Lightweight, JSR-330 compliant dependency injection library.
* [Governator ★526](Netflix/governator) - Extensions and utilities that enhance Google Guice.
* [Guice ★5110](google/guice) - Lightweight and opinionated framework that completes Dagger.
* [HK2](https://hk2.java.net) - Lightweight and dynamic dependency injection framework.

## Development

*Augmentation of the development process at a fundamental level.*

* [AspectJ](https://eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
* [DCEVM](http://dcevm.github.io/) - Modification of the JVM that allows unlimited redefinition of loaded classes at runtime.
* [Faux Pas ★14](zalando/faux-pas) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions.
* [HotswapAgent ★750](HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition.
* [JavaParser ★1101](javaparser/javaparser) - Parse, modify and generate Java code.
* [JavaSymbolSolver ★131](javaparser/javasymbolsolver) - A symbol solver for Java.
* [JRebel ![c]](http://zeroturnaround.com/software/jrebel/) - Instantly reloads code and configuration changes without redeploys.
* [Spring Loaded ★1667](spring-projects/spring-loaded) - Class reloading agent.

## Distributed Applications

*Libraries and frameworks for writing distributed and fault-tolerant applications.*

* [Apache Geode](http://geode.apache.org/) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
* [Apache Storm](http://storm.apache.org/) - Realtime computation system.
* [Apache ZooKeeper](http://zookeeper.apache.org/) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
* [Atomix](http://atomix.io/atomix/) - Fault-tolerant distributed coordination framework.
* [Axon Framework](http://www.axonframework.org/) - Framework for creating CQRS applications.
* [Copycat](http://atomix.io/copycat/) - Fault-tolerant state machine replication framework.
* [Dropwizard Circuit Breaker ★18](mtakaki/dropwizard-circuitbreaker) - Circuit breaker design pattern for dropwizard.
* [Hazelcast ![c]](http://hazelcast.org/) - Highly scalable in-memory datagrid with a free open-source version.
* [Hystrix ★9745](Netflix/Hystrix) - Provides latency and fault tolerance.
* [JGroups](http://www.jgroups.org/) - Toolkit for reliable messaging and creating clusters.
* [Orbit](http://www.orbit.cloud/) - Virtual actors; adds another level of abstraction to traditional actors.
* [Quasar](http://www.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
* [Zuul ★2600](Netflix/zuul) - A gateway service that provides dynamic routing, monitoring, resiliency, security, and more.

## Distributed Databases

*Databases in a distributed system that appear to applications as a single data source.*

* [Apache Cassandra](http://cassandra.apache.org) - Column-oriented and providing high availability with no single point of failure.
* [Apache HBase](http://hbase.apache.org) - Hadoop database for big data.
* [Druid](http://druid.io) - Real-time and historical OLAP data store that excels at aggregation and approximation queries.
* [Infinispan](http://infinispan.org/) - Highly concurrent key/value datastore used for caching.
* [OpenTSDB](http://opentsdb.net) - Scalable and distributed time series database written on top of Apache HBase.
* [OrientDB](https://orientdb.com/orientdb/) - Embeddable distributed database written on top of Hazelcast.

## Distribution

*Tools that handle the distribution of applications in native formats.*

* [Bintray ![c]](https://bintray.com/) - Version control for binaries that handle publishing. Compatible with Maven or Gradle, and has a free plan for open-source software as well as several business plans.
* [Boxfuse](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
* [Capsule](http://www.capsule.io/) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
* [Central Repository](http://search.maven.org/) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
* [IzPack](http://izpack.org/) - Setup authoring tool for cross-platform deployments.
* [JitPack](https://jitpack.io/) - Easy to use package repository for GitHub. Builds Maven/Gradle projects on demand and publishes ready-to-use packages.
* [Nexus ![c]](http://www.sonatype.com/nexus/solution-overview) - Binary management with proxy and caching capabilities.
* [packr ★1583](libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and Mac OS X.
* [really-executable-jars-maven-plugin ★85](brianm/really-executable-jars-maven-plugin) - Maven plugin for making self-executing JARs.

## Document Processing

*Libraries that assist with processing office document formats.*

* [Apache POI](http://poi.apache.org/) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
* [documents4j](http://documents4j.com) - API for document format conversion using third-party converters such as MS Word.
* [docx4j](http://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.

## Formal Verification

*Formal-methods tools: proof assistants, model checking, symbolic execution etc.*

* [CATG ★46 ⏳1Y](ksen007/janala2) - Concolic unit testing engine. Automatically generates unit tests using formal methods.
* [Checker Framework](http://types.cs.washington.edu/checker-framework/) - Pluggable type systems. Includes nullness types, physical units, immutability types and more.
* [Daikon](http://plse.cs.washington.edu/daikon/) - Detects likely program invariants and generates JML specs based on those invariants.
* [Java Path Finder (JPF)](http://babelfish.arc.nasa.gov/trac/jpf) - JVM formal verification tool containing a model checker and more. Created by NASA.
* [JMLOK 2.0](http://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected.
* [KeY](http://key-project.org/) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification.
* [OpenJML](http://openjml.github.io/) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers.

## Functional Programming

*Libraries that facilitate functional programming.*

* [cyclops-react ★581](aol/cyclops-react) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
* [derive4j ★255](derive4j/derive4j) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching, morphisms.
* [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
* [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
* [jOOλ ★1000](jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.
* [protonpack ★286](poetix/protonpack) - Collection of stream utilities.
* [StreamEx ★610](amaembo/streamex) - Enhances Java 8 Streams.
* [Vavr](http://www.vavr.io/) - Functional component library that provides persistent data types and functional control structures.

## Game Development

*Frameworks that support the development of games.*

* [jMonkeyEngine](https://jmonkeyengine.org/) - Game engine for modern 3D development.
* [libGDX](https://libgdx.badlogicgames.com/) - All-round cross-platform, high-level framework.
* [LWJGL](https://www.lwjgl.org/) - Robust framework that abstracts libraries like OpenGL/CL/AL.

## Geospatial

*Libraries for working with geospatial data and algorithms.*

* [Apache SIS](http://sis.apache.org/) - Library for developing geospatial applications.
* [Geo ★184](davidmoten/geo) - GeoHash utilities in Java.
* [Geotoolkit.org](http://www.geotoolkit.org/) - Library for developing geospatial applications. Built on top of the Apache SIS project.
* [GeoTools](http://geotools.org/) - Library that provides tools for geospatial data.
* [GraphHopper ★1198](graphhopper/graphhopper) - Road routing engine. Used as Java library or standalone web service.
* [H2GIS](http://www.h2gis.org/) - A spatial extension of the H2 database.
* [Jgeohash](http://astrapi69.github.io/jgeohash/) - Library for using the GeoHash algorithm.
* [Mapsforge ★450](mapsforge/mapsforge) - Map rendering based on OpenStreetMap data.
* [Spatial4j ★387](locationtech/spatial4j) - General purpose spatial/geospatial library.

## GUI

*Libraries to create modern graphical user interfaces.*

* [JavaFX](http://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html) - The successor of Swing.
* [Scene Builder](http://gluonhq.com/open-source/scene-builder/) - Visual layout tool for JavaFX applications.
* [SWT](http://www.eclipse.org/swt/) - The Standard Widget Toolkit, a graphical widget toolkit.

## High Performance

*Everything about high performance computation, from collections to specific libraries.*

* [Agrona ★793](real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications.
* [Disruptor](http://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
* [Eclipse Collections ★291](eclipse/eclipse-collections) - Collections framework inspired by Smalltalk.
* [fastutil](http://fastutil.di.unimi.it/) - Fast and compact type-specific collections.
* [HPPC](http://labs.carrotsearch.com/hppc.html) - Primitive collections.
* [JCTools ★1085](JCTools/JCTools) - Concurrency tools currently missing from the JDK.
* [Koloboke](https://github.com/OpenHFT/Koloboke) - Hash sets and hash maps.

## HTTP Clients

*Libraries that assist with creating HTTP requests and/or binding responses.*  

* [Async Http Client ★3704](AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library.
* [Feign](https://github.com/Netflix/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
* [OkHttp](http://square.github.io/okhttp/) - HTTP+SPDY client.
* [restQL-core ★42](B2W-BIT/restQL-core) - Microservice query language that fetches information from multiple services.
* [Retrofit](http://square.github.io/retrofit/) - Type-safe REST client.
* [Ribbon ★1362](Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud.
* [Riptide ★34](zalando/riptide) - Client-side response routing for Spring's RestTemplate.

## Hypermedia Types

*Libraries that handle serialization to hypermedia types.*

* [JSON-LD ★202](jsonld-java/jsonld-java) - JSON-LD implementation.
* [Siren4J ★12](eserating/siren4j) - Library for the Siren specification.

## IDE

*Integrated development environments that try to simplify several aspects of development.*

* [Eclipse](http://www.eclipse.org/) - Established open-source project with support for lots of plugins and languages.
* [IntelliJ IDEA ![c]](http://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
* [NetBeans](https://netbeans.org/) - Provides integration for several Java SE and EE features, from database access to HTML5.

## Imagery

*Libraries that assist with the creation, evaluation or manipulation of graphical images.*

* [Imgscalr](https://github.com/thebuzzmedia/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.
* [Tess4J ★220](nguyenq/tess4j) - A JNA wrapper for Tesseract OCR API.
* [Thumbnailator ★780](coobird/thumbnailator) - High-quality thumbnail generation library.
* [TwelveMonkeys ★522](haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats.
* [ZXing ★13660](zxing/zxing) - Multi-format 1D/2D barcode image processing library.

## JSON

*Libraries for serializing and deserializing JSON to and from Java objects.*

* [HikariJSON ★84](brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson.
* [Genson](http://owlike.github.io/genson/) - Powerful and easy to use Java-to-JSON conversion library.
* [Gson ★8856](google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
* [Jackson-datatype-money ★50](zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.
* [JSON-io ★196](jdereg/json-io) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer.
* [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
* [LoganSquare ★2899](bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.
* [Moshi ★2784](square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map.

## JSON Processing

*Libraries for processing data in JSON format.*

* [fastjson ★9209](alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding.
* [Jolt ★422](bazaarvoice/jolt) - JSON to JSON transformation tool.
* [JsonPath](https://github.com/jayway/JsonPath) - Extract data from JSON using XPATH-like syntax.
* [JsonSurfer ★55](jsurfer/JsonSurfer) - Streaming JsonPath processor dedicated to processing big and complicated JSON data.

## JVM and JDK

*Current implementations of the JVM/JDK.*

* [Avian ★945](ReadyTalk/avian) - JVM with both JIT and AOT modes. Includes an iOS port.
* [JDK 9](https://jdk9.java.net/) - Early access releases of JDK 9.
* [OpenJDK](http://openjdk.java.net/) - Open-source implementation for Linux.
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS.
* [Zulu OpenJDK 9](http://zulu.org/zulu-9-pre-release-downloads/) - Early access OpenJDK 9 builds for Windows, Linux, and Mac OS X.
* [Zulu OpenJDK](http://www.azul.com/downloads/zulu/) - OpenJDK builds for Windows, Linux, and Mac OS X through Java 8.

## Logging

*Libraries that log the behavior of an application.*

* [Apache Log4j 2](http://logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
* [Graylog](https://www.graylog.org/) - Open-source aggregator suited for extended role and permission management.
* [Kibana](https://www.elastic.co/products/kibana) - Analyzes and visualizes log files. Some features require payment.
* [Logback](http://logback.qos.ch/) - Robust logging library with interesting configuration options via Groovy.
* [Logbook ★76](zalando/logbook) - Extensible, open-source library for HTTP request and response logging.
* [Logstash](https://www.elastic.co/products/logstash) - Tool for managing log files.
* [SLF4J](http://www.slf4j.org/) - Abstraction layer/simple logging facade.
* [tinylog](http://www.tinylog.org/) - Lightweight logging framework with static logger class.
* [Tracer ★52](zalando/tracer) - Call tracing and log correlation in distributed systems.

## Machine Learning

*Tools that provide specific statistical algorithms for learning from data.*

* [Apache Flink](https://flink.apache.org/) - Fast, reliable, large-scale data processing engine.
* [Apache Mahout](https://mahout.apache.org/) - Scalable algorithms focused on collaborative filtering, clustering and classification.
* [Apache Spark](http://spark.apache.org/) - Data analytics cluster-computing framework.
* [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
* [DeepDive](http://deepdive.stanford.edu) - Creates structured information from unstructured data and integrates it into an existing database.
* [Deeplearning4j](http://deeplearning4j.org/) - Distributed and multi-threaded deep learning library.
* [H2O](http://www.h2o.ai/) - Analytics engine for statistics over big data.
* [JSAT ★271](EdwardRaff/JSAT) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution.
* [Oryx 2 ★1118](OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.
* [Smile](http://haifengl.github.io/smile/) - The Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

## Messaging

*Tools that help send messages between clients to ensure protocol independency.*

* [Aeron ★2774](real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport.
* [Apache ActiveMQ](http://activemq.apache.org/) - Message broker that implements JMS and converts synchronous to asynchronous communication.
* [Apache Camel](http://camel.apache.org/) - Glues together different transport APIs via Enterprise Integration Patterns.
* [Apache Kafka](http://kafka.apache.org/) - High-throughput distributed messaging system.
* [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
* [JeroMQ ★1275](zeromq/jeromq) - Implementation of ZeroMQ.
* [Nakadi ★136](zalando/nakadi) - Provides a RESTful API on top of Kafka.
* [RocketMQ ★3780](alibaba/RocketMQ) - A fast, reliable, and scalable distributed messaging platform.
* [Smack ★1340](igniterealtime/Smack) - Cross-platform XMPP client library.

## Miscellaneous

*Everything else.*

* [Codename One](https://www.codenameone.com/) - Cross-platform solution for writing native mobile (iOS, Android, etc.) apps.
* [CQEngine ★488](npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections.
* [Design Patterns ★19318](iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns.
* [Failsafe ★1705](jhalterman/failsafe) - Simple failure handling with retries and circuit breakers.
* [J2ObjC ★4746](google/j2objc) - Java to Objective-C translator for porting Android libraries to iOS.
* [javaslang-circuitbreaker](https://github.com/javaslang/javaslang-circuitbreaker) - Functional fault tolerance library.
* [JBot ★649](ramswaroop/jbot) - Framework for building chat bots.
* [JavaX](http://javax.ai1.lol/) - Reinventing and extending Java with a focus on simplicity.
* [JBake](http://jbake.org) - Static website generator.
* [Jimfs ★1228](google/jimfs) - In-memory file system.
* [Joda-Money](http://www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
* [JPad](http://jpad.io/) - Snippet runner.
* [Lanterna ★535](mabe02/lanterna) - Easy console text GUI library similar to curses.
* [LightAdmin](http://lightadmin.org/) - Pluggable CRUD UI library for rapid application development.
* [Membrane Service Proxy ★151](membrane/service-proxy) - An open-source, reverse proxy framework written in Java.
* [Modern Java - A Guide to Java 8 ★7057](winterbe/java8-tutorial) - Popular Java 8 guide.
* [Modernizer ★152](andrewgaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs.
* [OpenRefine](http://openrefine.org/) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
* [Polyglot for Maven ★456](takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allow the POM model to be written in dialects other than XML.
* [TypeTools ★270](jhalterman/typetools) - Tools for resolving generic types.

## Microservice

*Tools for managing microservices, i.e. creation, coordination or discovery.*

* [Apollo](https://spotify.github.io/apollo/) - Libraries for writing composable microservices.
* [consul-api ★152](Ecwid/consul-api) - Client for the [Consul](https://www.consul.io/) API: a distributed, highly available and datacenter-aware registry/discovery service.
* [Eureka ★3370](Netflix/eureka) - REST-based service registry for resilient load balancing and failover.
* [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.

## Monitoring

*Tools that monitor applications in production.*

* [AppDynamics ![c]](https://www.appdynamics.com/) - Performance monitor.
* [Glowroot](https://glowroot.org/) - Open-source Java APM.
* [Automon ★387](stevensouza/automon) - Combines the power of AOP with monitoring and/or logging tools.
* [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
* [JavaMelody ★875](javamelody/javamelody) - Performance monitoring and profiling.
* [jmxtrans ★1167](jmxtrans/jmxtrans) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.
* [Jolokia](https://jolokia.org/) - JMX over REST.
* [Kamon](http://www.kamon.io/) - Tool for monitoring applications running on the JVM.
* [Metrics](http://metrics.dropwizard.io/) - Expose metrics via JMX or HTTP and send them to a database.
* [New Relic ![c]](http://newrelic.com/) - Performance monitor.
* [nudge4j ★84](lorenzoongithub/nudge4j) - Remote developer console from the browser for Java 8 via bytecode injection.
* [OverOps ![c]](https://www.overops.com/) - In-production error monitoring and debugging.
* [Pinpoint ★3747](naver/pinpoint) - Open-source APM tool.
* [Prometheus](https://prometheus.io/) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
* [SPM ![c]](https://sematext.com/spm/) - Performance monitor with distributing transaction tracing for JVM apps.
* [Stagemonitor ★973](stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps.
* [Sysmon ★130](palantir/Sysmon) - Lightweight platform monitoring tool for Java VMs.

## Native
*For working with platform-specific native libraries.*

* [JavaCPP ★1946](bytedeco/javacpp) - Provides efficient and easy access to native C++.
* [JNA ★3030](java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.
* [JNR ★410](jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama/).

## Natural Language Processing

*Libraries that specialize in processing text.*

* [CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis.
* [DKPro](https://dkpro.github.io/) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
* [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

## Networking

*Libraries for building network servers.*

* [Comsat ★414](puniverse/comsat) - Integrates standard Java web-related APIs with Quasar fibers and actors.
* [Finagle ★5721](twitter/finagle) - Extensible RPC system for constructing high-concurrency servers. It implements uniform client and server APIs for several protocols, and is protocol-agnostic to simplify implementation of new protocols.
* [Grizzly](https://grizzly.java.net/) - NIO framework. Used as a network layer in Glassfish.
* [gRPC ★2755](grpc/grpc-java) - RPC framework based on protobuf and HTTP/2.
* [MINA](https://mina.apache.org/) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
* [Netty](http://netty.io/) - Framework for building high-performance network applications.
* [Nifty ★686](facebook/nifty) - Implementation of Thrift clients and servers on Netty.
* [Undertow](http://undertow.io/) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly.
* [urnlib ★5](slub/urnlib) - Represent, parse and encode URNs as in RFC 2141.

## ORM

*APIs that handle the persistence of objects.*

* [SimpleFlatMapper ★127](arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper.
* [Apache Cayenne](http://cayenne.apache.org/) - Provides clean, static API for data access. Also includes GUI Modeler for working with database mappings, DB reverse engineering and generation.
* [Ebean](http://ebean-orm.github.io/) - Provides simple and fast data access.
* [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
* [Hibernate](http://hibernate.org/orm/) - Robust and widely used with an active community.
* [MyBatis](http://www.mybatis.org/mybatis-3/) - Couples objects with stored procedures or SQL statements.

## PaaS

*Java platform as a service.*

* [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - AWS-based, with support for Tomcat and Jetty.
* [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - Serverless computation.
* [Google App Engine ![c]](https://cloud.google.com/) - PaaS on Google's infrastructure.
* [Heroku ![c]](https://www.heroku.com/) - Abstract computing environments.
* [Jelastic ![c]](https://jelastic.com/) - Supports Tomcat, Jetty, GlassFish, JBoss, TomEE and WildFly.
* [OpenShift Enterprise ![c]](https://www.openshift.com/) - On-premise solution.

## PDF

*Tools to help with PDF file creation.*

* [Apache FOP](http://xmlgraphics.apache.org/fop/) - Creates PDFs from XSL-FO.
* [Apache PDFBox](http://pdfbox.apache.org/) - Toolbox for creating and manipulating PDFs.
* [Dynamic Jasper](http://dynamicjasper.com/) - Abstraction layer to JasperReports.
* [DynamicReports](http://dynamicreports.org/) - Simplifies JasperReports.
* [flyingsaucer ★826](flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer.
* [iText ![c]](http://itextpdf.com/) - Creates PDF files programmatically.
* [JasperReports](http://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine.

## Performance analysis

*Tools for performance analysis, profiling and benchmarking.*

* [fastThread ![c]](http://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
* [GCeasy ![c]](http://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
* [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - An low-overhead, bias-free sampling profiler.
* [jHiccup ★345](giltene/jHiccup) - Logs and records platform JVM stalls.
* [JITWatch ★1102](AdoptOpenJDK/jitwatch) - Analyze the JIT compiler optimisations made by the HotSpot JVM.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - JMH is a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM.
* [JProfiler ![c]](https://www.ej-technologies.com/products/jprofiler/overview.html) - Profiler.
* [LatencyUtils ★272 ⏳1Y](LatencyUtils/LatencyUtils) - Utilities for latency measurement and reporting.
* [XRebel ![c]](http://zeroturnaround.com/software/xrebel/) - Profiler for web applications.
* [YourKit Java Profiler ![c]](https://www.yourkit.com/features/) - Profiler.

## Platform

*Frameworks that are suites of multiple libraries encompassing several categories.*

* [CUBA Platform](https://cuba-platform.com) - High level framework for development of enterprise applications with rich web interface, based on Spring, EclipseLink and Vaadin.
* [Light-Java](https://github.com/networknt/light-java) - A fast, lightweight and productive microservices framework with [security ★38](networknt/light-oauth2) built in.
* [Orienteer ★66](OrienteerBAP/Orienteer) - Open source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications.
* [Spring](http://projects.spring.io/spring-framework/) - Provides many packages ranging from dependency injection to aspect-oriented programming to security.


## Reactive libraries

*Libraries for developing reactive applications.*

* [Akka](http://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
* [Reactive Streams ★1687](reactive-streams/reactive-streams-jvm) - Provide a standard for asynchronous stream processing with non-blocking backpressure.
* [Reactor](http://projectreactor.io/) - Library for building reactive fast-data applications.
* [RxJava ★24565](ReactiveX/RxJava) - Library for composing asynchronous and event-based programs using observable sequences from the JVM.
* [vert.x](http://vertx.io/) - Polyglot event-driven application framework.

## REST Frameworks

*Frameworks specifically for creating RESTful services.*

* [Dropwizard](https://dropwizard.github.io/dropwizard/) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
* [Jersey](https://jersey.java.net/) - JAX-RS reference implementation.
* [Microserver ★747](aol/micro-server) — A convenient extensible Microservices plugin system for Spring & Spring Boot, with over 30 plugins and growing, that supports both micro-monolith and pure microservices styles.
* [Rapidoid](http://www.rapidoid.org/) - A simple, secure and extremely fast framework consisting of embedded HTTP server, GUI components and dependency injection.
* [rest.li ★1576](linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using type-safe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.
* [RESTEasy](http://resteasy.jboss.org/) - Fully certified and portable implementation of the JAX-RS specification.
* [RestExpress ★741](RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack to provide scaling and performance.
* [Restlet Framework ★522](restlet/restlet-framework-java) - Pioneering framework with powerful routing and filtering capabilities, unified client and server API.
* [Spark](http://sparkjava.com/) - Sinatra inspired framework.

## Science

*Libraries for scientific computing, analysis and visualization.*

* [DataMelt](http://jwork.org/dmelt/) - Environment for scientific computation, data analysis and data visualization.
* [Erdos ★64](Erdos-Graph-Framework/Erdos) - Modular, light and easy graph theoretic framework.
* [GraphStream](http://graphstream-project.org/) - Library for modeling and analysis of dynamic graphs.
* [JGraphT ★872](jgrapht/jgrapht) - Graph library that provides mathematical graph-theory objects and algorithms.
* [JGraphX ★376](jgraph/jgraphx) - Library for visualisation (mainly Swing) and interaction with node-edge graphs.
* [Mines Java Toolkit ★6](MinesJTK/jtk) - Library for geophysical scientific computation, visualization and digital signal analysis.
* [Tablesaw ★566](lwhite1/tablesaw) - Includes a data-frame, an embedded column-store, and hundreds of methods to transform, summarize, or filter data.

## Search

*Engines which index documents for search and analysis.*

* [Apache Lucene](https://lucene.apache.org/) - High-performance, full-featured cross-platform text search engine library.
* [Apache Solr](http://lucene.apache.org/solr/) - Enterprise search engine optimized for high volume traffic.
* [Elasticsearch](https://www.elastic.co/) - Distributed, multitenant-capable full-text search engine with a RESTful web interface and schema-free JSON documents.

## Security

*Libraries that handle security, authentication, authorization or session management.*

* [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
* [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
* [Cryptomator](https://cryptomator.org/) - Multiplatform transparent client-side encryption of files in the cloud.
* [Hdiv ★117](hdiv/hdiv) - Runtime application self-protection against OWASP Top 10 security risks such us Insecure Direct Object References, SQL injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF) and much more.
* [jjwt ★1763](jwtk/jjwt) - Java JWT: JSON Web Token for Java and Android.
* [Keycloak](http://keycloak.jboss.org/) - Integrated SSO and IDM for browser apps and RESTful web services.
* [Keyczar ★876](google/keyczar) - Easy to use, yet safe encryption framework with key versioning.
* [Nbvcxz ★81](GoSimpleLLC/nbvcxz) - Advanced password strength estimation.
* [OACC](http://oaccframework.org/) - Provides permission-based authorization services.
* [pac4j ★871](pac4j/pac4j) - Security engine.
* [PicketLink](http://picketlink.org/) - Umbrella project for security and identity management.

## Serialization

*Libraries that handle serialization with high efficiency.*

* [FlatBuffers ★7839](google/flatbuffers) - Memory efficient serialization library that can access serialized data without unpacking and parsing it.
* [FST ★762](RuedigerMoeller/fast-serialization) - JDK compatible high performance object graph serialization.
* [Kryo ★2646](EsotericSoftware/kryo) - Fast and efficient object graph serialization framework.
* [MessagePack ★726](msgpack/msgpack-java) - Efficient binary serialization format.

## Server

*Servers which are specifically used to deploy applications.*

* [Apache Tomcat](http://tomcat.apache.org/) - Robust all-round server for Servlet and JSP.
* [Apache TomEE](http://tomee.apache.org/) - Tomcat plus Java EE.
* [Jetty](http://www.eclipse.org/jetty/) - Lightweight, small server, often embedded in projects.
* [nanohttpd ★2770](NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server.
* [WebSphere Liberty](https://developer.ibm.com/wasdev/) - Lightweight, modular server developed by IBM.
* [WildFly](http://www.wildfly.org/) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.

## Template Engine

*Tools which substitute expressions in a template.*

* [Handlebars.java](http://jknack.github.io/handlebars.java/) - Logic-less and semantic Mustache templates.
* [Jtwig](http://jtwig.org/) - Modular, configurable and fully tested template engine.
* [Thymeleaf](http://www.thymeleaf.org/) - Aims to be a substitute for JSP and works for XML files in general.

## Testing

*Tools that test from model to the view.*

* [Apache JMeter](http://jmeter.apache.org/) - Functional testing and performance measurements.
* [ArchUnit ★112](TNG/ArchUnit) - Architecture test library, to specify and assert architecture rules.
* [Arquillian](http://arquillian.org/) - Integration and functional testing platform for Java EE containers.
* [AssertJ](http://joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
* [Awaitility](https://github.com/jayway/awaitility) - DSL for synchronizing asynchronous operations.
* [Burst ★388](square/burst) - A unit testing library for varying test data.
* [Citrus](http://citrusframework.org/) - Integration testing framework with focus on client- and serverside messaging.
* [ConcurrentUnit ★197](jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications.
* [Cucumber ★1469](cucumber/cucumber-jvm) - BDD testing framework.
* [Cukes-REST ★32](ctco/cukes-rest) - A collection of Gherkin steps for REST-service testing using Cucumber.
* [Galen ★1045](galenframework/galen) - Layout and functional testing framework for websites.
* [Gatling](http://gatling.io/) - Load testing tool designed for ease of use, maintainability and high performance.
* [GreenMail](http://www.icegreen.com/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL.
* [J8Spec ★37 ⏳1Y](j8spec/j8spec) - J8Spec is a library that allows tests written in Java to follow the BDD style introduced by RSpec and Jasmine.
* [JBehave](http://jbehave.org/) - Framework for Behavioural Driven Development.
* [JFairy ★302](Codearte/jfairy) - Fake data generator.
* [Fixture Factory ★200](six2six/fixture-factory) - Generates fake objects from a template.
* [JGiven](http://jgiven.org) - Developer-friendly BDD testing framework compatible with JUnit and TestNG.
* [JMockit](http://jmockit.org/) - Mocks static, final methods and more.
* [JSONAssert](http://jsonassert.skyscreamer.org/) - Simplifies testing of JSON strings.
* [junit-dataprovider ★125](TNG/junit-dataprovider) - A TestNG like dataprovider runner for JUnit.
* [JUnitParams](https://pragmatists.github.io/JUnitParams/) - Creation of readable and maintainable parametrised tests.
* [Lamdba Behave ★191 ⏳1Y](RichardWarburton/lambda-behave) - Descriptive behavioural specification framework.
* [Mockito ★4675](mockito/mockito) - Creation of test double objects in automated unit tests for the purpose of TDD or BDD.
* [MockServer](http://www.mock-server.com/) - Allows mocking of systems that are integrated with HTTP/S.
* [Moco ★1734](dreamhead/moco) - Concise web services for stubs and mocks, Duke's Choice Award 2013.
* [Mutability Detector ★132](MutabilityDetector/MutabilityDetector) - Reports on whether instances of a given class are immutable.
* [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test-suites.
* [pojo-tester](http://www.pojo.pl/) - Automatically performs tests on basic POJO-methods.
* [PowerMock](https://github.com/jayway/powermock) - Enables mocking of static methods, constructors, final classes and methods, private methods and removal of static initializers.
* [raml-tester ★63](nidi3/raml-tester) - Tests if a request/response matches a given RAML definition.
* [Randomized Testing ★99](randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.
* [REST Assured](https://github.com/jayway/rest-assured) - Java DSL for easy testing for REST/HTTP services.
* [Selenide](http://selenide.org/) - Concise API around Selenium to write stable and readable UI tests.
* [Selenium](http://docs.seleniumhq.org/) - Portable software testing framework for web applications.
* [Spock ★1545](spockframework/spock) - Spock is a developer testing and specification framework for Java and Groovy applications.
* [TestContainers ★466](testcontainers/testcontainers-java) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.
* [Truth ★1027](google/truth) - Google's assertion and proposition framework.
* [WireMock](http://wiremock.org/) - Stubs and mocks web services.

## Utility

*Libraries which provide general utility functions.*

* [Apache Commons](http://commons.apache.org/) - Provides different general purpose functions like configuration, validation, collections, file upload or XML processing.
* [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others.
* [Dex ★735](PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization.
* [Embulk](http://www.embulk.org/) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
* [Gephi ★2022](gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks.
* [Guava ★16658](google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
* [JADE](http://jade.tilab.com/) - Framework and environment for building and to debugging multi-agent systems.
* [JavaVerbalExpressions ★1363](VerbalExpressions/JavaVerbalExpressions) - A library that helps to construct difficult regular expressions.
* [JGit](https://eclipse.org/jgit/) - A lightweight pure Java library implementing the Git version control system.
* [minio-java ★49](minio/minio-java) - Provides simple APIs to access any Amazon S3 compatible object storage server.
* [Protégé](http://protege.stanford.edu/) - Provides an ontology editor and a framework to build knowledge-based systems.
* [Underscore-java ★132](javadev/underscore-java) - Port of Underscore.js functions.

## Version Managers

*Utilities that help setup the development shell environment and switch between different Java versions.*

* [jabba ★239](shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux, Windows.
* [jenv ★1454](gcuisinier/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and Mac OS X.
* [SDKMan ★1406](sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.

## Web Crawling

*Libraries that analyze the content of websites.*

* [Apache Nutch](http://nutch.apache.org/) - Highly extensible, highly scalable web crawler for production environment.
* [Crawler4j ★2018](yasserg/crawler4j) - Simple and lightweight web crawler.
* [JSoup](http://jsoup.org/) - Scrapes, parses, manipulates and cleans HTML.

## Web Frameworks

*Frameworks that handle the communication between the layers of an web application.*

* [Apache Tapestry](http://tapestry.apache.org/) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
* [Apache Wicket](http://wicket.apache.org/) - Component-based web application framework similar to Tapestry with a stateful GUI.
* [Blade ★2148](biezhi/blade) - Lightweight, modular framework which aims to be elegant and simple.
* [Bootique](http://bootique.io/) - Minimally opinionated framework for runnable apps.
* [Grails](https://grails.org/) - Groovy framework with the aim to provide a highly productive environment by favoring convention over configuration, no XML and support for mixins.
* [Jooby](http://jooby.org) - Scalable, fast and modular micro framework which offers multiple programming models.
* [Ninja](http://www.ninjaframework.org/) - Full stack web framework.
* [Pippo](http://www.pippo.ro/) - Small, highly modularized Sinatra-like framework.
* [Play](https://www.playframework.com/) - Uses convention over configuration, hot code reloading and display of errors in the browser.
* [PrimeFaces](http://primefaces.org/) - JSF framework which has a free and a commercial version with support. Provides several frontend components.
* [Ratpack](https://ratpack.io/) - Set of libraries that facilitate fast, efficient, evolvable and well tested HTTP applications.
* [Spring Boot](http://projects.spring.io/spring-boot/) - Microframework which simplifies the development of new Spring applications.
* [Vaadin](https://vaadin.com/home) - Event-driven framework build on top of GWT. Uses server-side architecture with Ajax on the client-side.

# Resources

## Awesome Lists

*Awesome lists related to the Java/JVM ecosystem*

- [ciandcd ★401](ciandcd/awesome-ciandcd)
- [Awesome Gradle Plugins ★80](ksoichiro/awesome-gradle)
- [Awesome JVM ★403](deephacks/awesome-jvm)
- [Awesome REST ★1163](marmelab/awesome-rest)
- [Useful Java Links ★3023](Vedenin/useful-java-links)

## Communities

*Active discussions.*

* [r/java](https://www.reddit.com/r/java) - Subreddit for the Java community.
* [stackoverflow](http://stackoverflow.com/questions/tagged/java) - Question/answer platform.
* [vJUG](http://virtualjug.com/) - Virtual Java User Group.

## Frontends

*Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one.*

* [java.libhunt.com](https://java.libhunt.com/)

## Influential Books

*Books that had a high impact and are still worth reading.*

* [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
* [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
* [Effective Java (2nd Edition)](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)
* [Java Concurrency in Practice](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java](http://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

## Podcasts

*Something to listen to while programming.*

* [Java Off Heap](http://www.javaoffheap.com/)
* [The Java Council](http://virtualjug.com/podcast/)
* [The Java Posse](http://www.javaposse.com/) - Discontinued as of 02/2015.

## Twitter

*Active accounts to follow. Descriptions from Twitter.*

* [Adam Bien](https://twitter.com/AdamBien/) - Freelancer: Author, JavaONE Rockstar Speaker, Consultant, Java Champion.
* [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance Geek, Benchmarking Tzar, Concurrency Bug Hunter.
* [Antonio Goncalves](https://twitter.com/agoncal/) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
* [Arun Gupta](https://twitter.com/arungupta/) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
* [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
* [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
* [Ed Burns](https://twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
* [Eugen Paraschiv](https://twitter.com/baeldung) - Author of the Spring Security Course.
* [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
* [Java EE](https://twitter.com/Java_EE/) - Official Java EE Twitter account.
* [Java Magazine](https://twitter.com/Oraclejavamag) - Official Java Magazine account.
* [Java](https://twitter.com/java/) - Official Java Twitter account.
* [Javin Paul](https://twitter.com/javinpaul) - Well-known Java blogger.
* [Lukas Eder](https://twitter.com/lukaseder) - Java Champion, speaker, JUG.ch co-leader, Founder and CEO Data Geekery (jOOQ).
* [Mario Fusco](https://twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
* [Mark Reinhold](https://twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
* [Markus Eisele](https://twitter.com/myfear) - Java EE evangelist, Red Hat.
* [Martijn Verburg](https://twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
* [Martin Thompson](https://twitter.com/mjpt777) - Pasty faced performance gangster.
* [OpenJDK](https://twitter.com/OpenJDK) - Official OpenJDK account.
* [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
* [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
* [Simon Maple](https://twitter.com/sjmaple) - Java Champion, virtualJUG founder, LJC leader, RebelLabs author.
* [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion, speaker.
* [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.

## Websites

*Sites to read.*

* [Google Java Style](https://google.github.io/styleguide/javaguide.html)
* [InfoQ](http://www.infoq.com/)
* [Java Algorithms and Clients](http://algs4.cs.princeton.edu/code/)
* [Java, SQL, and jOOQ](http://blog.jooq.org/)
* [Java.net](https://community.oracle.com/community/java)
* [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
* [JavaWorld](http://www.javaworld.com/)
* [JAXenter](https://jaxenter.com/)
* [RebelLabs](http://zeroturnaround.com/rebellabs/)
* [The Takipi Blog](http://blog.takipi.com/)
* [TheServerSide.com](http://www.theserverside.com/)
* [Vanilla Java](https://vanilla-java.github.io/)
* [Voxxed](https://www.voxxed.com/)

# Contributing

Contributions are very welcome!

Please have a look at [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) for guidelines.

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
---
<p align="center">
	This list is a copy of <a href="akullpp/awesome-java">akullpp/awesome-java</a> with ranks
</p>