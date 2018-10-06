![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build status](https://img.shields.io/travis/ramnes/awesome-mongodb.svg)](https://travis-ci.org/ramnes/awesome-mongodb)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Books](#books)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [More](#more)
 - [Libraries](#libraries)
   - [C](#c)
   - [C++](#c-1)
   - [C#/.NET](#cnet)
   - [Delphi](#delphi)
   - [Elixir](#elixir)
   - [Erlang](#erlang)
   - [Go](#go)
   - [Haskell](#haskell)
   - [Java](#java)
   - [JavaScript](#javascript)
   - [Julia](#julia)
   - [Lisp](#lisp)
   - [Mathematica](#mathematica)
   - [Perl](#perl)
   - [PHP](#php)
   - [Python](#python)
   - [R](#r)
   - [Ruby](#ruby)
   - [Rust](#rust)
   - [Scala](#scala)
 - [Tools](#tools)
   - [Administration](#administration)
   - [Big Data](#big-data)
   - [Deployment](#deployment)
   - [Desktop](#desktop)
   - [Development](#development)
   - [Monitoring](#monitoring)
   - [Shell](#shell)
   - [Web](#web)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.com/manual/introduction/)
 - [MongoDB documentation](https://docs.mongodb.com/manual/)
 - [MongoDB tutorials](https://docs.mongodb.com/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Books
 - [Builder Book](https://builderbook.org/book) - Learn how to build a full stack JavaScript web app from scratch
 - [MongoDB Applied Design Patterns (Rick Copeland)](http://shop.oreilly.com/product/0636920027041.do)
 - [The Little MongoDB Book](https://www.openmymind.net/2011/3/28/The-Little-MongoDB-Book/) - Basic introduction

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data
 - [Kubernetes examples](https://github.com/kubernetes/examples/tree/master/staging/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on Kubernetes

### More
 - [MongoDB source code](https://github.com/mongodb/mongo)
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud) - MongoDB Inc. cloud offer
 - [mLab](https://mlab.com/) - Fully managed MongoDB-as-a-Service (formerly MongoLab)
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)
 - [Atlas](https://www.mongodb.com/cloud/atlas) - Fully automated cloud service engineered and run by the same team that builds the database.

## Libraries
### C
 - [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - Official C driver

### C++
 - [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver

### C#/.NET ###
 - [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver
 - [mongo-queue-csharp](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue on top of MongoDB
 - [MongoDB Messaging](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library
 - [MongoRepository](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver

### Delphi
 - [TMongoWire](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver

### Elixir
 - [mongodb](https://github.com/ankhers/mongodb) - Community Elixir driver
 - [mongodb_ecto](https://github.com/ankhers/mongodb_ecto) - Adapter for the Ecto database wrapper

### Erlang
 - [mongodb-erlang](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver

### Go
 - [mgo](https://github.com/go-mgo/mgo) - Community Go driver

### Haskell
 - [mongodb](https://github.com/mongodb-haskell/mongodb/) - Community Haskell driver

### Java
 - [Jongo](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell
 - [Hibernate OGM](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores
 - [mongo-java-driver](https://github.com/mongodb/mongo-java-driver) - Official Java driver
 - [mongo-queue-java](https://github.com/gaillard/mongo-queue-java) - Java message queue on top of MongoDB
 - [mongoFS](https://github.com/dbuschman7/mongoFS) - An enhancement of GridFS to allow for more features and capabilities
 - [Mongojack](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs
 - [Morphia](https://github.com/MorphiaOrg/morphia) - Java ODM ("Object-Document Mapper")
 - [Morphium](https://github.com/sboesebeck/morphium) - Java ODM and caching layer
 - [Mungbean](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM
 - [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories

### JavaScript
 - [Camo](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases
 - [MEAN.JS](https://github.com/meanjs/mean) - Full stack based on MongoDB, Express, AngularJS, and Node.js
 - [MERN (mern-starter)](https://github.com/Hashnode/mern-starter) - Full stack based on MongoDB, Express, React and Node.js
 - [Meteor](https://github.com/meteor/meteor) - Real-time/reactive client-server framework based on MongoDB, with lots of features
 - [Mongoose](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM
 - [CASL Mongoose](https://github.com/stalniy/casl/tree/master/packages/casl-mongoose) - Permissions management library integrated with Mongoose
 - [mongration](https://github.com/awapps/mongration) - Node.js migration framework
 - [Moonridge](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io
 - [node-mongodb-native](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver

### Julia
 - [Mongo.jl](https://github.com/Lytol/Mongo.jl) - C driver bindings

### Lisp
 - [cl-mongo](https://github.com/fons/cl-mongo) - Community Common Lisp interface
 - [mongo-cl-driver](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver

### Mathematica
 - [MongoDBLink](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver

### Perl
 - [mongo-perl-driver](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver

### PHP
 - [Doctrine MongoDB](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality
 - [eloquent-mongodb-repository](https://github.com/LaravelRepository/eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb
 - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel
 - [mongodb-repository](https://github.com/PHPRepository/mongodb-repository) - Repository implementation
 - [pecl/mongodb](https://github.com/mongodb/mongo-php-driver) - Official PHP driver

### Python
 - [Flask-Stupe](https://github.com/numberly/flask-stupe) - Flask extension that adds PyMongo support to Flask
 - [MongoEngine](https://github.com/MongoEngine/mongoengine) - ODM on top of PyMongo
 - [MongoLog](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler
 - [Mongo-Thingy](https://github.com/numberly/mongo-thingy) - The most idiomatic and friendly-yet-powerful ODM
 - [Motor](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado or asyncio
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver
 - [minimongo](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface
 - [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy
 - [μMongo](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow

### R
 - [mongolite](https://github.com/jeroen/mongolite) - Fast and simple client for R

### Ruby
 - [awesome_explain](https://github.com/sandboxws/awesome_explain) - A simple global method to explain Mongoid queries
 - [mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver
 - [Mongoid](https://github.com/mongodb/mongoid) - ODM framework

### Rust
 - [mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver for Rust 1.x and MongoDB 3.0.x

### Scala
 - [mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver
 - [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver
 - [Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL

## Tools
### Administration
 - [mongo_fdw](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper
 - [mongoctl](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations
 - [MongoDB Smasher](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your setup
 - [mongodb-tools](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes
 - [Mongolastic](https://github.com/ozlerhakan/mongolastic) - MongoDB to Elasticsearch (and vice-versa) migration tool
 - [MongoMultiMaster](https://github.com/rick446/mmm) - Multi-master replication
 - [MoSQL](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication
 - [mtools](https://github.com/rueckstiess/mtools) - Collection of scripts to set up test environments and visualize log files
 - [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from GridFS
 - [nginx-mongodb-rest](https://github.com/minhajuddin/nginx-mongodb-rest) - REST client written as an Nginx module
 - [pt-mongodb-query-digest](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-query-digest.html) - Aggregates queries from query profiler and reports query usage statistics
 - [pt-mongodb-summary](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-summary.html) - MongoDB cluster status overview command line tool

### Big Data
 - [mongo-hadoop](https://github.com/mongodb/mongo-hadoop) - Hadoop connector

### Deployment
 - [ansible-role-mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role
 - [chef-mongodb](https://github.com/edelight/chef-mongodb) - Chef cookbook
 - [Dockerfile](https://github.com/dockerfile/mongodb)
 - [Helm Chart](https://github.com/helm/charts/tree/master/stable/mongodb)
 - [puppet-mongodb](https://github.com/voxpupuli/puppet-mongodb) - Puppet module (formerly puppetlabs-mongodb)

### Desktop
 - [dbKoda](https://www.dbkoda.com) - Cross-platform and open-source IDE
 - [MongoHub](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client
 - [Mongotron](http://mongotron.io/) - Cross-platform and open-source client built with Electron
 - [NoSQLBooster](https://nosqlbooster.com) - Feature-rich but easy-to-use cross-platform IDE (formerly MongoBooster)
 - [Robo 3T](https://github.com/Studio3T/robomongo) - Free, native and cross-platform shell-centric GUI (formerly Robomongo)
 - [Studio 3T](https://studio3t.com/) - Cross-platform GUI, stable and powerful (formerly MongoChef)

### Development
 - [mgodatagen](https://github.com/feliixx/mgodatagen) - Random data generator
 - [Mongo Playground](https://mongoplayground.net) - Online query playground
 - [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Node.js library, CLI and Docker image for populating databases using JS and JSON files
 - [Mongoeye](https://github.com/mongoeye/mongoeye) - Schema and data analyzer: explore data in your collections
 - [Variety](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog/) - SaaS-based monitoring
 - [Mongoop](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting
 - [Motop](https://github.com/tart/motop) - MongoDB top clone
 - [mtop](https://github.com/beaufour/mtop) - Another top clone
 - [mongo-monitor](https://github.com/dwmkerr/mongo-monitor) - Simple monitoring CLI
 - [mongo-munin](https://github.com/erh/mongo-munin) - Collection of Munin plugins
 - [mongomon](https://github.com/pcdummy/mongomon) - More Munin plugins
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)
 - [Percona Monitoring and Management](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Free and open-source platform for managing and monitoring databases performances

### Shell
 - [mongo-hacker](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements

### Web
 - [adminMongo](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs
 - [Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. commercial online GUI and data-visualization platform
 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [mongo-express](https://github.com/mongo-express/mongo-express) - Web-based admin interface built with Express
 - [mongoadmin](https://github.com/thomasst/mongoadmin) - Admin interface built with Django
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface written in JavaScript
 - [Rockmongo](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of

## Applications

Those open-source applications have MongoDB somewhere in their stack:

 - [Builder Book App](https://github.com/builderbook/builderbook) - Web app to publish books or documentation built with React and Express
 - [CodeCombat](https://github.com/codecombat/codecombat) - Multiplayer programming game for learning how to code
 - [Countly](https://github.com/countly/countly-server) - Mobile & web analytics and marketing platform built with Node.js
 - [Leanote](https://github.com/leanote/leanote) - Evernote clone built with Go
 - [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software ("built for the modern web")
 - [Quokka](https://github.com/rochacbruno/quokka) - Python CMS built with Flask
 - [Reaction](https://github.com/reactioncommerce/reaction) - Event-driven, real-time commerce platform built with ES6
 - [SaaS Boilerplate](https://github.com/async-labs/saas) - Boilerplate for SaaS products, built with TypeScript, React and Express
 - [uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application built with Node.js and Bootstrap

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.
