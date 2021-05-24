# SmartchainDB Driver

This repo contains driver code for the extended version of [BigchainDB Driver](https://github.com/bigchaindb/java-bigchaindb-driver). In addition to interacting with the Server instance, it includes supports for preparing and sending custom/new transactions such as Request-For-Quote, Bid, and Accept-Bid, and also holds logic for interacting with the Kafka cluster and Semantic Engine. It implements a simple kafka producer for publishing the request events and contains the simulation module to execute the experimentations.

 The driver can be used with the native BigChainDB server if the events of interest are in the class of transactions currently supported by the BigChainDB. For the event types based on extensions to the BigChainDB transaction model, an upgraded server will be required and can be requested but is not being made public at the current time.
