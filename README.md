# HashRing

A minimal implementation of consistent hashing as described in [Consistent
Hashing and Random Trees: Distributed Caching Protocols for Relieving Hot
Spots on the World Wide Web] (https://www.akamai.com/es/es/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf)
Clients can use the `HashRing` struct to add consistent hashing to their
applications. `HashRing`'s API consists of three methods: `add`, `remove`,
and `get` for adding a node to the ring, removing a node from the ring, and
getting the node responsible for the provided key.

## Example

Below is a simple example of how an application might use `HashRing` to make
use of consistent hashing. Since `HashRing` exposes only a minimal API clients
can build other abstractions, such as virtual nodes, on top of it. The example
below shows one potential implementation of virtual nodes on top of `HashRing`

TODO