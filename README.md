# Cloud Co Network Upgrade and VLAN Design  

## Project Overview  
This project involves the design and configuration of a secure, efficient, and scalable network infrastructure for **Cloud Co**, a networking company with headquarters in Kuala Lumpur and remote branches in Singapore and Australia. Using **Cisco Packet Tracer**, the project focuses on implementing VLANs, wireless configurations, routing protocols, server setups, and security mechanisms to meet organizational requirements.  

---

## Network Requirements Implemented  
- **DHCPv4**  
  - Configured to operate across multiple LANs.  

- **Australia Branch (WLAN & WLC)**  
  - Wireless LAN Controller (WLC) configured with VLAN interface.  
  - DHCP server and WPA2 authentication implemented.  
  - Optional RADIUS server support.  

- **Routing**  
  - IPv4 static and dynamic routing.  
  - Configured **OSPF** and default static routes.  

- **Security**  
  - Mitigated Layer 2 (L2) attacks with **port security**.  
  - Implemented **HSRP (Hot Standby Router Protocol)** for redundancy.  
  - Configured **EtherChannel** for link aggregation.  

- **Server Farm (Singapore Branch)**  
  - Configured **FTP, DNS, and Web Servers**.  

- **Basic Configurations**  
  - Deployed essential switch and router configurations.  
  - Logical topology built and validated using Cisco Packet Tracer.  

---

## Departments & Locations  
- **Kuala Lumpur (HQ)**: Management, Human Resources, Design  
- **Singapore (Remote)**: Finance, R&D, Server Farm  
- **Australia (Remote)**: Delivery, Management, IT  

---

## Tools & Technologies  
- **Cisco Packet Tracer**  
- VLAN, WLAN, WLC, OSPF, HSRP, EtherChannel  
- DHCP, FTP, DNS, Web Services  

---

## Key Learnings  
- Designing enterprise-level VLAN-based topologies with inter-branch connectivity.  
- Implementing **WLC-based WLANs** with secure authentication methods.  
- Applying **dynamic routing protocols** (OSPF) alongside static routing.  
- Enhancing network reliability with redundancy protocols and EtherChannel.  
- Configuring **network services** (FTP, DNS, Web) within a Server Farm.  
- Understanding and mitigating **Layer 2 security threats**.  
