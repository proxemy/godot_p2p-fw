# Roadmap to create a p2p framework for the godot game engine.

## Network structure and peer management

A basic p2p node needs 4 kinds of protokoll messages to communicate with other
nodes.

* Join
* Leave
* Bootstrap/Request routing table
* Find node

with these 4 messages an 'organized' (with GUIDs) mesh network can be
binary searched to find and peer with log(n) complexity.
see 'Kademlia distributed hashtable DHT'.



