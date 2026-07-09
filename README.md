# My-Networking-journey
### 📅 2026-06-24
- **Core Focus:** Network Basics & Cisco iOS Commands
- **Platform Used:** YouTube (NetworkChuck CCNA) & Terminal Simulation
- **What I Mastered:** - Learned the difference between a Hub (broadcasts to all), a Switch (targets specific MAC addresses), and an Access Point (extends wired networks to Wi-Fi).
  - Executed my first Cisco commands: `enable` to enter privileged mode and `show mac-address-table` to see how a switch maps out a network.
  - Embraced the learning curve by failing a quiz—and understanding *why* the answers were wrong!

---
### 📅 2026-06-25
- **Core Focus:** Routers, DNS, and Advanced Routing Tables
- **Platform Used:** YouTube (NetworkChuck CCNA)
- **What I Mastered:** - Understood that a Router is required to connect two completely different networks; a standard switch cannot do this.
  - Learned that DNS acts as the internet's phonebook, translating human-friendly URLs (like google.com) into computer-friendly IP addresses.
  - Explored advanced Cisco CLI commands: `show ip route` to view local routing maps, and `show bgp ipv4 unicast` to look at global internet routing paths.

---
### 📅 2026-06-27
- **Core Focus:** OSI Model and TCP/IP Model Foundations
- **Platform Used:** YouTube (NetworkChuck CCNA)
- **What I Mastered:** - Learned that network communication is broken down into layered models (OSI and TCP/IP) to standardize how data travels.
  - Focused on Layer 2 (Data Link layer) where MAC addresses and switches operate, and Layer 3 (Network layer) where IP addresses and routers handle global paths.
  - Understood how data flows down the stack on the sending device and back up the stack on the receiving device.

---
### 📅 2026-07-02
- **Core Focus:** Practical Implementation of OSI & TCP/IP Models
- **Platform Used:** CCNA Practical Lab / TryHackMe
- **What I Mastered:** - Explored the deep details of the OSI and TCP/IP layers through hands-on implementation.
  - Learned how packet encapsulation works practically: seeing how data is wrapped in a Transport header (ports), then a Network header (IPs), and finally a Data Link header (MACs).
  - Understood how to read and trace a packet as it moves up and down the network stack.

---
### 📅 2026-07-03
- **Core Focus:** OSI Model Top Layers (Application, Presentation, Session, & Transport)
- **Platform Used:** YouTube (NetworkChuck CCNA Episode 5)
- **What I Mastered:** 
  - Learned how streaming a YouTube video uses the upper OSI layers to request, translate, and manage data.
  - Understood that Layer 7 (Application) uses HTTPS to request data, Layer 6 (Presentation) handles data compression and encryption, and Layer 5 (Session) keeps the communication channel open.
  - Explored Layer 4 (Transport) where data is broken down into segments and prepared for delivery using protocols like TCP or QUIC for seamless streaming.

---
### 📅 2026-07-04
- **Core Focus:** Network Design Topologies (2-Tier, 3-Tier, & Layer 3 Switching)
- **Platform Used:** YouTube (NetworkChuck CCNA)
- **What I Mastered:** 
  - Learned the 3-Tier Network Design: Access Layer (connecting end devices), Distribution Layer (handling routing policies and security), and Core Layer (high-speed network backbone).
  - Understood the 2-Tier (Collapsed Core) Design, which merges the Core and Distribution layers to save cost and complexity in smaller environments.
  - Explored Multilayer Switches (Layer 3 Switches) and learned how they blend switching capabilities with routing functions to move traffic between subnets faster.

---
### 📅 2026-07-05
- **Core Focus:** Data Center Architecture (Leaf-Spine vs. 3-Tier Design)
- **Platform Used:** CCNA Class & Practical Concepts
- **What I Mastered:** - Learned the difference between North-South traffic (user-to-internet) and East-West traffic (server-to-server inside a data center).
  - Understood why the traditional 3-tier campus design causes bottlenecks and latency for server-to-server traffic due to data loops and Spanning Tree Protocol (STP).
  - Mastered the Leaf-Spine Architecture: A flat, two-layer topology where every server is exactly two hops away from another, allowing predictable low-latency, full link utilization (ECMP), and massive scalability.

---
### 📅 2026-07-07
- **Core Focus:** WAN Connectivity & Traffic Optimization (MPLS, VPN, QoS)
- **Platform Used:** CCNA Class & Practical Concepts
- **What I Mastered:** - Learned enterprise WAN technologies: Dedicated Leased Lines, high-speed Label-switching (MPLS), localized Metro Ethernet (M-Eth), and legacy cell-based ATM networks.
  - Understood how VPNs provide a cost-effective way to tunnel encrypted corporate data securely over the public internet.
  - Explored QoS (Quality of Service) and how it prioritizes time-sensitive voice/video traffic over standard data to prevent network congestion.
  - Nailed the daily quiz options with significantly improved accuracy!

---
### 📅 2026-07-08
- **Core Focus:** Home Network Hardening, Nmap Recon, & External Port Scanning
- **Platform Used:** CCNA / Hands-on Lab & Pentest-tools.com
- **What I Mastered:** - Explored home router security configurations to prevent unauthorized access and exposure.
  - Practiced Nmap reconnaissance commands: `-sT` (TCP Connect scan), `-O` (OS fingerprinting), `-p` (targeting specific ports), and `--script vuln` (automating vulnerability detection).
  - Used external port scanning tools (Pentest-tools.com) to audit perimeter exposure on my public IP address.

---
### 📅 2026-07-09
- **Core Focus:** Hybrid Cloud Architecture Concepts
- **Platform Used:** CCNA / Networking Class
- **What I Mastered:** - Understood the architecture of Hybrid Cloud environments connecting private data centers with public cloud infrastructure (AWS/Azure).
  - Learned the trade-offs between private cloud control/compliance and public cloud scalability.
  - Explored how organizations leverage hybrid models to balance security, performance, and operational costs.

---


