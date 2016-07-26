![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
  - [Documentation](#documentation)
  - [Articles](#articles)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [More](#more)
 - [Libraries](#libraries)
  - [C](#c)
  - [C++](#c-1)
  - [C#/.NET](#cnet)
  - [Delphi](#delphi)
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
  - [Clients](#clients)
    - [GUI](#gui)
    - [Shell](#shell)
    - [Web](#web)
  - [Deployment](#deployment)
  - [Monitoring](#monitoring)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.org/manual/core/introduction/)
 - [MongoDB documentation](https://docs.mongodb.org/manual/)
 - [MongoDB tutorials](https://docs.mongodb.org/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](http://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Write a Tumblelog Application with Flask and MongoEngine](https://docs.mongodb.org/ecosystem/tutorial/write-a-tumblelog-application-with-flask-mongoengine/) - Nice Python tutorial hidden into the official Python driver documentation

### More
 - [MongoDB source code](https://github.com/mongodb/mongo)
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [MongoLab](https://mongolab.com/) - Fully managed MongoDB-as-a-Service
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - Official C driver

### C++
 - [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver

### C#/.NET ###
 - [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver
 - [mongo-queue-csharp](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library
 - [MongoRepository](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver

### Delphi
 - [TMongoWire](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver

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
 - [mongo-queue-java](https://github.com/gaillard/mongo-queue-java) - Java message queue backed by MongoDB
 - [mongoFS](https://github.com/dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities
 - [Mongojack](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs
 - [Morphia](https://github.com/mongodb/morphia) - Official Java ODM
 - [Morphium](https://github.com/sboesebeck/morphium) - Java ODM and caching layer
 - [Mungbean](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM
 - [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB

### JavaScript
 - [Camo](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases
 - [MEAN.JS](https://github.com/meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js
 - [MERN (mern-starter)](https://github.com/Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js
 - [Mongoose](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM
 - [mongration](https://github.com/eberhara/mongration) - Node.js migration framework
 - [Moonridge](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io
 - [node-mongodb-native](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver

### Julia
 - [Mongo.jl](https://github.com/Lytol/Mongo.jl) - Bindings on MongoDB official C driver

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
 - [eloquent-mongodb-repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb
 - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel
 - [mongodb-repository](https://github.com/PHPRepository/php-mongodb-repository) - Repository implementation
 - [pecl/mongodb](https://github.com/mongodb/mongo-php-driver) - Official PHP driver

### Python
 - [Flask-PyMongo](https://github.com/dcrosta/flask-pymongo) - PyMongo support for Flask applications
 - [MongoEngine](https://github.com/MongoEngine/mongoengine) - Python ODM on top of PyMongo
 - [MongoLog](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler
 - [Motor](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado applications
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver
 - [minimongo](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface
 - [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy
 - [μMongo](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow

### R
 - [mongolite](https://github.com/jeroenooms/mongolite) - Fast and Simple MongoDB Client for R

### Ruby
 - [mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver
 - [Mongoid](https://github.com/mongodb/mongoid) - Ruby ODM framework

### Rust
 - [mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x

### Scala
 - [mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver
 - [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver
 - [Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL

## Tools
### Administration
 - [mongo_fdw](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB
 - [mongoctl](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations
 - [MongoDB Smasher](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup
 - [mongodb-tools](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes
 - [MongoMultiMaster](https://github.com/rick446/mmm) - Multi-Master MongoDB replication
 - [MoSQL](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication
 - [mtools](https://github.com/rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files
 - [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS
 - [nginx-mongodb-rest](https://github.com/minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module
 - [Variety](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content

### Big Data
 - [mongo-hadoop](https://github.com/mongodb/mongo-hadoop) - MongoDB connector for Hadoop

### Clients
#### GUI
 - [HumongouS.io](https://www.humongous.io) - Web based GUI
 - [MongoChef](http://3t.io/mongochef) - Cross-platform MongoDB manager, stable and powerful
 - [MongoHub](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client
 - [Robomongo](https://github.com/paralect/robomongo) - Native and cross-platform MongoDB manager

#### Shell
 - [mongo-hacker](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements

#### Web
 - [adminMongo](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs
 - [mongo-express](https://github.com/mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3
 - [mongoadmin](https://github.com/thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of

### Deployment
 - [ansible-role-mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role
 - [chef-mongodb](https://github.com/edelight/chef-mongodb) - Chef cookbook
 - [puppetlabs-mongodb](https://github.com/puppetlabs/puppetlabs-mongodb) - Puppet module
 - [Dockerfile](https://github.com/dockerfile/mongodb)

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Mongoop](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting
 - [Motop](https://github.com/tart/motop) - MongoDB top clone
 - [mtop](https://github.com/beaufour/mtop) - Another top clone
 - [mongo-munin](https://github.com/erh/mongo-munin) - Collection of Munin plugins
 - [mongomon](https://github.com/pcdummy/mongomon) - More Munin plugins
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)

## Applications
 - [Leanote](https://github.com/leanote/leanote) - Evernote clone built with Go and MongoDB
 - [Quokka](https://github.com/quokkaproject/quokka) - Python CMS built on top of Flask and MongoDB
 - [uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.
