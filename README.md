# java-cli-buildr-cockroachdb-multi-node-without-ssl-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

A java buildr build, that connects to 3 node cluster
cockroach database without ssl.

## Tech stack
- java
- buildr
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
