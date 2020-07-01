# Expanding an Offline Data Collection Application into a Cloud-Ready FOS Data Architecture

Overview: As our various legacy data collection systems became obsolete and increasingly difficult to maintain, migrating them to modern web technologies and a microservice architecture had many advantages. Offline data collection coupled with reliable synchronization to a central database was the key requirement of the system. Apache CouchDB, a NoSQL database with a "battle-tested" offline sync capability, made for simple implementation, as well as filling another requirement of being a free open-source (FOS) solution. However, there were many limitations to overcome to make this a viable solution: security considerations, migrating legacy RDBMS data, and providing scientific staff an accessible and performant way to access data via SQL. I will outline and demonstrate how I chose to solve these challenges in a forward-looking approach that will scale well to future cloud deployment.

# References

* https://pouchdb.com/
* https://docs.couchdb.org/en/stable/
* https://developer.ibm.com/technologies/blockchain/tutorials/implement-custom-solution-kubernetes-cluster-couchdb-ibm-cloud/
* https://nuetzlich.net/gocryptfs/
* https://www.percona.com/software/mongodb/percona-server-for-mongodb
* https://nifi.apache.org/
* https://drill.apache.org/
* OpenAPI https://swagger.io/specification/
