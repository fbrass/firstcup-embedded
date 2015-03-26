# First Cup Embedded
The [First Cup Example](http://docs.oracle.com/javaee/6/firstcup/doc/) is a JEE7 Example.

The project was to get the First Cup example into an embedded environment with maven.

## Features
- [JEE7](http://docs.oracle.com/javaee/7/tutorial/doc/home.htm) web profile application
- [JPA 2.x](http://docs.oracle.com/javaee/7/tutorial/doc/persistence-intro.htm#BNBPZ)
- [Maven](https://maven.apache.org/)
- [Glassfish] (https://glassfish.java.net/de/)
- [derby] (https://db.apache.org/derby/)
- ...

## Requirements
- [Java 7]
- [Maven]

## Running
- mvn clean package run
- mvn embedded-glassfish:run
it didnt work the first time cause derby needed to be configured. RUN IT AGAIN!!!

TADA WORKS :)