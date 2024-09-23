# NPS
This repository contains a series of **Network Protocol Security** experiments carried out with **Cisco Packet Tracer**. These experiments focused on implementing and testing various network security protocols to ensure secure data transmission, authentication, and threat prevention across enterprise network environments.

## Objectives
The main objectives of these experiments were to:
- Implement security protocols to protect network communication.
- Simulate common network security attacks and test defense mechanisms.
- Evaluate the impact of encryption and authentication on network performance.
- Strengthen network infrastructures by applying security best practices.

## Experiments Overview

1. **Network Topology Design for Security**:  
   - Built secure network architectures with routers, switches, and end devices.  
   - Segmented networks with VLANs and deployed DMZ for added security layers.

2. **Implementation of Security Protocols**:
   - **IPSec**: Configured IPSec tunnels to encrypt IP traffic, ensuring confidentiality and integrity between remote sites.
   - **SSL/TLS**: Secured web traffic with SSL/TLS, encrypting communication between client and server.
   - **SSH**: Enabled SSH for secure remote device management, replacing Telnet with encrypted sessions.
   - **802.1X Authentication**: Applied port-based access control to enforce authentication on wired and wireless networks.
   
3. **Defense Against Attacks**:
   - **ARP Spoofing**: Simulated ARP spoofing attacks and implemented dynamic ARP inspection to prevent them.
   - **DHCP Starvation**: Simulated DHCP starvation attacks and applied DHCP snooping to block rogue DHCP servers.
   - **Man-in-the-Middle (MITM) Attacks**: Conducted MITM simulations and applied ACLs (Access Control Lists) to mitigate unauthorized access.

4. **Traffic Encryption and VPN Setup**:
   - Configured **VPN tunnels** (site-to-site and remote-access) using IPSec to secure communication between distributed network segments.
   - Applied GRE over IPSec to allow multiprotocol traffic over the secure tunnels.

5. **Access Control and Network Hardening**:
   - Created and applied **ACLs** to control traffic flow, allowing or denying specific types of traffic based on IP, port, and protocol.
   - Configured **Port Security** on switches to prevent MAC address flooding attacks and unauthorized device connections.

## Results
- **IPSec & VPNs**: Successfully established secure communication channels with encrypted traffic, ensuring data confidentiality and integrity.
- **SSH & 802.1X**: Enhanced network management security through encrypted remote sessions and port-based authentication.
- **Attack Mitigation**: Effectively prevented ARP spoofing, DHCP starvation, and MITM attacks using DAI, DHCP snooping, ACLs, and port security.
- **Performance Impact**: Observed minimal latency increases due to encryption but overall maintained high network performance while securing data.

## Key Technologies
- **Cisco Packet Tracer**: Used as the primary tool for network security simulations.
- **Protocols**: IPSec, SSL/TLS, SSH, 802.1X, ACLs, VPN, GRE, DHCP Snooping, ARP Inspection.
  
## Conclusion
These experiments provided practical knowledge of configuring and securing network infrastructures against various security threats. They demonstrate the importance of encryption, authentication, and access control in modern networks.

Explore the `.pkt` files included in the repository to simulate these scenarios and implement your own security enhancements.
