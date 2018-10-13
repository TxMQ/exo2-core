Aviator Core Framework for Hashgraph Application Development
===================================================

Aviator is a framework for developing applications on the Swirlds Hashgraph platform.  Primarily, Aviator offers features and an application architecture for getting transactions into a Hashgraph, processing those transactions once they've been accepted, and logging transactions out to persistent storage.

Aviator was developed to provide the features that Swirlds' SDK lacks that I knew I would need to develop real-world applications.  I'm sure other folks have needs and ideas that aren't on my radar yet, so I would encourage feature requests and development submissions from other Hashgraph developers.  The framework will only improve for everyone as more people get involved.

Aviator Core Framework was formerly known as the Exo2 Framework.  It is designed to be more flexible, easier to build on, and offers a better ability to monitor transactions as they move through the processing lifecycle than Exo.  

Features
--------

Aviator Core implements the following feature set:
- Socket-based messaging for Java applications (in-progress)
- Web socket-based messaging for anything that can make use of a web socket.
- REST-based messaging for anything that can make HTTP requests
- An event-driven framework for invoking processing logic on transactions at each step in the transaction life cycle
- A framework for logging processed transactions to a blockchain-based transaction log (blockchain the data structure, not blockchain the platform)

### More Information
There's more to learn about building Aviator applications.  First, check out the (Aviator Zoo Demo Application)[https://github.com/txmq/aviator-zoo-demo] and see how the demo is put together.  It illustrates all of the concepts currently supported by Aviator, and is dockerized so you can easily run the application stack.

When you're ready to dive into development, check the [docs folder](docs/README.md) for additional README files that describe how to use each feature in more detail.
