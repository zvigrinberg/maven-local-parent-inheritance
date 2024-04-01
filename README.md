# Maven Local Parent Inheritance
Simple example to show how to inherit from parent groupId And version when omitted in pom.xml


## Procedure

1. Install parent pom on local repository 
```shell
mvn clean install -f sample-parent/pom.xml
```

2. Install pom on local repository
```shell
mvn clean install -f java-demo/pom.xml
```