# Week 2 Application layer
## Networking Layering and TCP/IP Model
**Layering** is a modular design which is used to simplify complex systems by dividing tasks into manageable layers

What are some benefits of layering?  
**Interoperability:** This allows standards to evolve independently without altering the TCP.  
**Scalability:** New technologies can replace individual layers without stopping the procceses.  
**Ease of debugging:** This isolates issues to specific layers(goes hand in hand with interoperability and scalability)

|Layer |Protocols |Functions |Protocol Data Unit|
|------|-----------|----------|------|
|Application |	HTTP, SMTP, DNS|	Encodes/decodes messages for applications|	Messages|
|Transport	|TCP (reliable), UDP (unreliable)|	Segments data, manages flow/congestion and manages the end-to-end communication|	Segments/Datagrams|
|Internet	|IPv4, IPv6|	Logical addressing, routing|	Datagrams|
|Link	|Ethernet, Wi-Fi|	Physical addressing (MAC), frame transmission|	Frames|

## Application Layer Fundamentals
**P2P or Peer-to-Peer Architecture features:**
**Decentralized:** No central server, pers can communicate directly.  
**Dynamic connectivity:** Peers can join/leave at any time.  
**Complex Management:** It does require algorithms to handle churn and coordination

|Aspect |Client -Server |P2P Arhitectures|
|---------------|----------------|--------|
|Scalability|Limited by server capacity| It scales with peers which meaning its self-scalable|
Reliability| Centralized(It has a single point of failure) | Distributed(It is resilient to node failures)|
|Examples include| HTTPS,SMTP, DNS| BitTorrent, Blockchain Networks|

