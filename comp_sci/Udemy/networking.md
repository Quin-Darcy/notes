# Notes for CompTIA Netorking+
---
### Network IDs
A WAN is two or more interconnected LANS. Each LAN in a WAN needs a unique identifier called a __network ID__. The network ID is consists of the parts of the IP addresses of the devices on a LAN which are the same. So if there are three computers on a LAN with IPs 10.0.0.5, 10.0.0.7, and 10.0.0.9, then 10.0.0.0 is the network ID.
Multiple LANs are connected through a router. Therefore, a router needs its own IP address.
The router interface that connects a single LAN to the router is known as a __default gateway__. Typically, the LAN-side NIC on the defualt gateway the lowest host address in the network. Using the example above, this would be 10.0.0.1. 

### Subnet Masking

