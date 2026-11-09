# Project 01: Small Office Network Design and Configuration

## 1. Project Overview

This project involves designing and configuring a small office network using Cisco Packet Tracer. The network represents an organization with two departments: Administration and ICT.

Each department operates on a separate IP network. A Cisco router connects the two departmental networks, allowing computers in both departments to communicate.

The project focuses on practical networking concepts, including IPv4 addressing, subnet masks, default gateways, router configuration, and network connectivity testing.

## 2. Project Objectives

- Design a small office network topology.
- Configure Cisco routers and switches.
- Assign IPv4 addresses to network devices.
- Configure router interfaces and default gateways.
- Establish communication between two separate networks.
- Test connectivity using ICMP ping.
- Identify and troubleshoot basic network problems.

## 3. Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4 addressing
- Ethernet networking
- ICMP
- Static IP addressing

## 4. Network Topology

The network consists of:

- One Cisco 2911 router.
- Two Cisco 2960 switches.
- Four desktop computers.
- One Laptop Computer
- Two Network Printers
- Ethernet connections.

**Network topology screenshot:**

<img width="1383" height="704" alt="project 1" src="https://github.com/user-attachments/assets/f2966134-79fe-4052-aa06-0ad55c67bcba" />


## 5. IP Addressing Scheme

| Department | Device | IP Address | Subnet Mask | Gateway |
| :--- | :--- | :--- | :--- | :--- |
| ICT | PC0 | 192.168.10.10 | 255.255.255.128 | 192.168.10.1 |
| ICT | PC1 | 192.168.10.11 | 255.255.255.128 | 192.168.10.1 |
| ICT | Laptop0 | 192.168.10.12 | 255.255.255.128 | 192.168.10.1 |
| ICT | Printer1 | 192.168.10.12 | 255.255.255.128 | 192.168.10.1 |
| Administration | PC2 | 192.168.10.10 | 255.255.255.128 | 192.168.10.129 |
| Administration | PC3 | 192.168.10.11 | 255.255.255.128 | 192.168.10.129 |
| Administration | PC4 | 192.168.10.12 | 255.255.255.128 | 192.168.10.129 |
| Administration | Printer0 | 192.168.10.12 | 255.255.255.128 | 192.168.10.129 |


## 6. Router Configuration

The router was configured with two Ethernet interfaces to connect the Administration and ICT networks.

[Insert your actual Cisco IOS configuration commands here.]

## 7. Network Testing and Verification

Connectivity was tested using the following commands:

- `ping` – to verify communication between devices.
- `show ip interface brief` – to check router interface status.
- `show ip route` – to inspect the routing table.
- `show arp` – to examine IP-to-MAC address mappings.

[Insert screenshots showing your actual successful ping tests.]

## 8. Troubleshooting

Document the problems encountered during implementation and how they were resolved.

Examples include:

- Incorrect IP address configuration.
- Wrong default gateway.
- Router interface shutdown.
- Incorrect network cable connections.
- Duplicate IP addresses.

Only include problems that you actually encountered or deliberately simulated.

## 9. Skills and Knowledge Gained

Through this project, I gained practical experience in network topology design, IPv4 addressing, Cisco IOS configuration, router interface management, default gateway configuration, and network troubleshooting.

I also developed a better understanding of how routers facilitate communication between different IP networks.

## 10. Project Files

The repository contains:

- Cisco Packet Tracer project file.
- Network topology screenshots.
- IP addressing documentation.
- Router configuration commands.
- Network connectivity test results.

## 11. Conclusion

This project provided practical experience in designing and implementing a small office network. It strengthened my understanding of basic network infrastructure and established a foundation for more advanced networking projects.

**Project Status:** [In Progress]
