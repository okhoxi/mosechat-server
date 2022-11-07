Mose
=========================
this is a IM chat project.

You need to have [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html) installed.

We build and test Apache Kafka with Java 8, 11 and 17. We set the `release` parameter in javac and scalac
to `8` to ensure the generated binaries are compatible with Java 8 or higher (independently of the Java version
used for compilation). Java 8 support has been deprecated since Apache Kafka 3.0 and will be removed in Apache
Kafka 4.0 (see [KIP-750](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=181308223) for more details).


### Build a jar and run it ###
mvn package


See [tests/README.md](doc/tests/README.md).

### Running in Vagrant ###

See [vagrant/README.md](doc/vagrant/README.md).

### Contribution ###
Mose is interested in building the community; 
we would welcome any thoughts . 
You can reach us [issue](https://github.com/okhoxi/mosechat-server/issues).
