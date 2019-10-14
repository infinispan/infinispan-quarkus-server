# infinispan-quarkus-server
Infinispan Quarkus Server

An Infinispan Server that runs on top of Quarkus runtime allowing for native binaries.

Authentication and Indexing are not supported currently.

## Building 

This branch uses both SNAPSHOT versions of Quarkus and Infinispan.
This can be useful when Infinispan is about to release a new version and wants to test to make sure it will work in Quarkus.

1. Compile Infinispan master
2. Compile Quarkus using `update_infinispan` branch https://github.com/wburns/quarkus/tree/update_infinispan
3. Compile Infinispan Quarkus Server `update_infinpsan` branch
