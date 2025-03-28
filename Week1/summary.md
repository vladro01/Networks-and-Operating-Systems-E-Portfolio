# Week 1: Introduction to Networks and OS

## What is a Network?
Definition: A network is a system of interconnected nodes also known as devices that exchange information with links  knows as communication channels.

Examples of networks:

Internet, transportation networks, sensor networks, telephone networks

## What are some of the key characteristics of the Internet?

Global Connectivity: It allows worldwide communication
Decentralization: It allows the Internet to have no single controlling authority.
Interoperability: Standard protocols include TCP/IP, HTTP which allows diverse systems to communicate. 
Scalability: The internet is scalable allowing billions of devices to connect, not limited to PC's only.
Multimedia support: It allows the transfer of text, audio and video
Real-time Communication: This includes tools like video conferencing
Ubiquity: The internet is accessible with mobile/wireless devices.

## Internet Structure:
Network edge: A network edge is the connection or interface between a device or local network and the internet. In other words it hosts clients/servers and end systems.
Access Networks:
Types include Residential such as DSL or cable, Institutional such as Ethernet and WiFi, and mobile such as 4G/5G.
This would also include physical media such as fiber,copper and wireless links.
Network core: Interconnected routers which forward packets via packet/circuit switching, some examples include tier-1 ISP backbones.

## Packet Switching
Process:

Segmentation: Hosts will  break data into packets ( MTU = 1500 bytes).

Store-and-Forward: Routers will buffer entire packets before trying retransmission.

Queuing: Packets will wait in buffers if output links are congested.

Routing: Forwarding tables direct packets via Dijkstra’s algorithm (OSPF).

The maths behind it:

Transmission Delay: 
Delay=L\R where L= packet size and R = link rate

End-to-End Delay: 
For N hops, total delay = N * L\R


## Circuit Switching
Mechanism: It allows for dedicated bandwidth allocation via FDM/TDM.

FDM: Frequency bands split for parallel channels an example would be cable TV.

TDM:  Are time slots allocated sequentially and an example would include legacy telephone networks. 

## Efficiency Comparison:

Packet Switching: This would be better suited  for bursty traffic such as  web browsing.

Circuit Switching: Guaranteed QoS or quality of service for real-time applications such as  VoIP or voice over   internet protocol. 

- VoIP is a network a communications technology which enables you to make phone calls using your broadband connection instead of landline service.

# Packet switching vs Circuit switching
## Packet Switching vs. Circuit Switching ##

| Aspect          | Packet Switching                          | Circuit Switching                  |
|----------------|--------------------------------|--------------------------------|
| Resource Usage | Shared (statistical multiplexing)  | Dedicated (FDM/TDM)            |
| Efficiency     | Better for bursty data (web browsing) | Guaranteed bandwidth (e.g., voice calls) |
| Scalability    | Supports more users (35 users on 1 Gbps) | Limited users (e.g., 10 users on 1 Gbps) |
| Example        | Internet data transfer            | Traditional telephone networks |

# Physical Media

Type		|Bandwidth		|Use Case			|Limitations|
|-----------|---------------|-------------------|-----------|
Fibre Optic	|10-100 Gbps		|Backbone links, data centres	|High installation cost
Twisted Pair	|1-10 Gbps (Cat 6)	|Ethernet LANs			|Susceptible to EMI
Wireless (WiFi)	|54-450 Mbps		|Mobile devices, IoT		|Limited range, interference

 ## The internet is formed:
Tier-1 ISP's: This is the global backbone Lumen, Deutsche Telekom  
Tier-2 ISP's: This would include Regional/local providers such as BT in the UK  
Content Providers: This would include private networks like Google's B4 SDN


