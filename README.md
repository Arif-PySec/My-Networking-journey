# 🚀 My Networking & Security Journey

## 📁 Phase 1: Networking Fundamentals

### 📅 Daily Logs

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

### 📅 2026-07-10
- **Core Focus:** Power over Ethernet (PoE, PoE+, PoE++) Architecture
- **Platform Used:** CCNA Class & Hardware Foundations
- **What I Mastered:** - Learned how Ethernet cables can simultaneously transmit data and DC electrical power to endpoints, eliminating the need for separate power supplies.
  - Mastered the PoE standards hierarchy: 
    - Standard PoE (802.3af up to 15.4W) for simple devices like IP phones.
    - PoE+ (802.3at up to 30W) for motorized PTZ cameras and advanced WAPs.
    - PoE++ (802.3bt up to 60W/100W) for heavy-duty hardware like laptops and smart displays.
  - Understood the concept of power delivery vs. power received due to line dissipation over copper links.

---

### 📅 2026-07-11
- **Core Focus:** Fiber Optic Infrastructure (Single-Mode, Multi-Mode, Layers & Connectors)
- **Platform Used:** CCNA Class & Hardware Foundations
- **What I Mastered:** 
  - Learned why Fiber Optics outperform copper Ethernet: immune to Electromagnetic Interference (EMI), superior security against physical taps, and capable of long-distance transmission without signal loss.
  - Mastered Single-Mode Fiber (SMF) vs. Multi-Mode Fiber (MMF): SMF uses lasers for long-haul WAN links, while MMF uses LEDs for short-distance, high-bandwidth data center connections.
  - Explored the protective layers of fiber cables (Core, Cladding, Buffer, Kevlar, Jacket) and identified primary connector types (LC, SC, ST).

---
### 📅 2026-07-12
- **Core Focus:** IP Addressing, Subnet Foundations, & Default Gateways
- **Platform Used:** CCNA Class & Practical Networking
- **What I Mastered:** 
  - Learned the structure of an IPv4 address, dividing the address into Network ID and Host ID.
  - Explored the role of the Default Gateway as the exit node for traffic leaving the local subnet.
  - Understood the subnet address pool math for a standard /24 network:
    - 256 Total Addresses (0 to 255).
    - 2 Reserved IPs: Network Address (.0) and Broadcast Address (.255).
    - 254 Usable Host IPs (1 to 254) for endpoints and gateway interfaces.

---
### 📅 2026-07-13
- **Core Focus:** Public vs. Private IPs, NAT, RFC 1918, & IPv6 Introduction
- **Platform Used:** CCNA Class & Practical Networking
- **What I Mastered:** 
  - Learned the difference between Public IPs (globally routable) and Private IPs (internal use defined by RFC 1918).
  - Memorized the RFC 1918 Private IP ranges (10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16).
  - Understood how NAT (Network Address Translation) translates multiple internal private IPs into a single public IP to save IPv4 address space.
  - Explored the fundamental differences between 32-bit IPv4 addresses and 128-bit IPv6 hexadecimal addresses.

---
### 📅 2026-07-15
- **Core Focus:** Binary and Decimal Conversions for Subnetting
- **Platform Used:** CCNA Class & Practical Exercises
- **What I Mastered:** 
  - Reviewed 8-bit binary positional values (128, 64, 32, 16, 8, 4, 2, 1) and their role in IPv4 octet construction.
  - Re-verified quick decimal-to-binary and binary-to-decimal mental conversions.
  - Prepared foundational bitwise math required for variable length subnet masking (VLSM) and CIDR notation.

---
### 📅 2026-07-15
- **Core Focus:** Demystifying Subnet Masks & Borrowing Bits
- **Platform Used:** CCNA / NetworkChuck Subnetting Series
- **What I Mastered:** 
  - Understood that a Subnet Mask isolates the Network ID (street) from the Host ID (house number) using binary 1s as a boundary marker.
  - Learned CIDR notation (/24, /25, etc.) and how it represents the total number of masked network bits.
  - Demystified "borrowing bits": converting host bits (0s) into network bits (1s) to carve a single larger network into multiple smaller, isolated subnets ($2^n$ subnets created).

---
### 📅 2026-07-16
- **Core Focus:** Practical Subnetting & Home Network Segmentation
- **Platform Used:** NetworkChuck Subnetting Series (Episode 4)
- **What I Mastered:** 
  - Fully mastered slicing a single parent network into multiple isolated subnets by borrowing bits from the host portion.
  - Applied key formulas to calculate subnet yields ($2^n$ where $n$ = borrowed bits) and usable host pools ($2^h - 2$ where $h$ = remaining host bits).
  - Practice-designed segmented networks using custom CIDR prefixes (/25, /26, /27) and identified block sizes, network IDs, and broadcast boundaries for each subnet.

---

### 📅 2026-07-18
- **Core Focus:** Host-Based Subnetting & Variable Length Subnet Masking (VLSM)
- **Platform Used:** CCNA / NetworkChuck Subnetting Series
- **What I Mastered:** 
  - Learned how to design subnets by reversing the math to target specific host requirements ($2^h - 2 \geq$ required hosts).
  - Mastered the core logic of Variable Length Subnet Masking (VLSM) to maximize IP address conservation across different sized network segments.
  - Practiced allocating custom CIDR prefixes (/26, /28, /30) to align precisely with department host sizes while minimizing waste.

---

### 📅 2026-07-19
- **Core Focus:** Subnetting Series Completion & Final Mastery
- **Platform Used:** NetworkChuck Subnetting Series (Completed!)
- **What I Mastered:** 
  - Successfully completed the entire foundational subnetting curriculum.
  - Solidified full command over binary/decimal conversions, network bit allocation ($2^n$), and host requirement planning ($2^h - 2$).
  - Developed the skills to architect optimized, zero-waste network infrastructures using Variable Length Subnet Masking (VLSM).
  - **Status:** Officially immune to getting tripped up by subnet masks, CIDR prefixes, or boundary math again!

---

## 📁 Phase 2: Ethical Hacking & Penetration Testing
- **Course:** Ethical Hacking in 15 Hours
- **Goal:** Master Reconnaissance, OSINT, Exploitation, and Active Directory

### 📅 Daily Logs
