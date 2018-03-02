# Saiku Enterprise Analytics with Apache Drill

This bundle is a basic Saiku Enterprise Analytics deployment with Apache Drill. It is designed to allow easy deployment of a sclable NOSQL OLAP analysis setup. The deployment of this bundle will deploy the following units:

* 1 Saiku Analytics Enterprise Edition
* 1 Apache Drill
* 1 Apache Zookeeper

## Usage

Deploy this bundle using juju:

juju deploy ~spiculecharms/saiku-drill
juju expose saikuanalytics-enterprise


## Interacting with the bundle

To make use of Saiku you need data. By default the Apache Drill installation is empty, add some data to it!