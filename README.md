# Maven Quickstart Archetype - Java 11 + JUnit5

## Summary
The project is a Maven archetype for Java 11 and JUnit5

## Prerequisites
* JDK 11
* Maven 3

## Install Archetype Locally

To install the archetype in your local repository execute the following commands:

```bash
git clone https://github.com/jeremycook123/java11-junit5-archetype.git
cd java11-junit5-archetype
mvn clean install
```

## Maven Create/Generate New Java Project

```bash
mvn archetype:generate \
 -DarchetypeGroupId=com.cloudacademy.devops \
 -DarchetypeArtifactId=java11-junit5-archetype \
 -DarchetypeVersion=1.0.0-SNAPSHOT \
 -DgroupId=com.example \
 -DartifactId=my-project \
 -DinteractiveMode=false
```
