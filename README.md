# Campus-Network-Scenarios

Project Description: Campus Network Scenarios

Short description:

The project is dedicated to the development and optimization of the campus network, taking into account modern requirements for performance, security and scalability. The main focus is on using NAT (Network Address Translation) for effective management of network resources, as well as configuring routing and data protection.

Project objectives:

✅ Development of the topology of the campus network, taking into account the segmentation and optimization of NAT.
✅ Implementation of Static NAT to increase fault tolerance and traffic control.
 Optimization of routing using OSPF and VLAN.
 Implementation of security mechanisms (Firewall, VPN, IDS/IPS).
✅ Analysis of the impact of Static NAT on network performance and optimization of its operation.

Network architecture:

🔹 Main network components:

The Main Campus is the central node of the network that manages traffic and provides access to corporate resources.
City Campus is a remote branch connected to the main campus via VPN.
Traffic Management system: using Static NAT and Port Address Translation (PAT) for load balancing.

Routing and NAT:

Configure Static NAT for stable network connections.
Using VRF Aware NAT to differentiate network segments.
OSPF optimization for automatic traffic balancing.

Security and fault tolerance:

Implementation of Firewall and IDS/IPS to protect against external threats.
Using a VPN for a secure connection between campuses.
Setting up QoS (Quality of Service) to prioritize traffic (VoIP, video conferencing).

Technologies and tools used:

Equipment: Cisco routers and switches
Software: Cisco Packet Tracer, Wireshark
Protocols: Static NAT, OSPF, VRF, VPN, VLAN
Security: Firewall, IDS/IPS, STUN/TURN

Project results:

🔹 Improved connection stability through the use of Static NAT.
🔹 Reduced network latency by 20% thanks to optimized OSPF routing.
Improve network security, including protection against DDoS attacks and unauthorized access.
Creating a scalable infrastructure ready for the expansion of the campus network.

Conclusions and prospects:

The project has demonstrated that proper NAT and routing configuration can significantly improve the efficiency of campus networks. In the future, it is possible to integrate SDN (Software-Defined Networking) for flexible traffic management and automated load balancing.
