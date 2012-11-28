canadensys-core
===============

Collection of utility functions used by Canadensys projects.

Features
--------
* Zip an entire folder (and its contents)
* Generic number parser : T parseNumber(String value, Class<T> targetClass)
* Roman numerals support

Usage
-----
Maven
```
<dependency>
	<groupId>net.canadensys</groupId>
	<artifactId>canadensys-core</artifactId>
	<version>1.1-SNAPSHOT</version>
</dependency>
```

Dependencies
------------
* [Apache Commons Lang 3.1](http://commons.apache.org/lang/)
* [Apache Commons Compress 1.4.1](http://commons.apache.org/compress/)
* [Apache Commons IO 2.4](http://commons.apache.org/io/)
* [Apache Maven 3](http://maven.apache.org/)

Build
-----
```
mvn package
```

Tests
-----
Unit tests
```
mvn test
```

Contributors
-----------
* Thoralf Gutierrez - Roman Numerals converter
