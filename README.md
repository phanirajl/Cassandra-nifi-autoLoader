Building processor
mvn install

Copy the build nifi-sample-nar-1.0-SNAPSHOT.nar file to nifi lib directory and restart nifi:
$ cp nifi-sample-nar/target/nifi-sample-nar-1.0-SNAPSHOT.nar NIFI_HOME/lib
$ NIFI_HOME/bin/nifi.sh start

Open a browser and navigate to the nifi UI at http://localhost:8080/nifi

On the Add Processor window, select "CassandraAutoLoad". 
