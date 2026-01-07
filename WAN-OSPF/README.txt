# WAN OSPF routing – Portfolio Project

# Overview
This project simulates a WAN connection between a Warsaw branch and Karków branch office using OSPF as the dynamic routing protocol.
The goal was to design a simple multi-site WAN topology and verify end-to-end connection.

The goal was:
- WAN design
- OSPF
- IP addressing for private LAN and public WAN)
- Loopback interfaces
- Connectiion tests

---

# Network Topology
- 3x Router 2911
- 2x Layer 2 2960 Switches
- 2x PCs 

Addressing:

- War LAN: 192.168.10.0/24
- Krk LAN: 192.168.20.0/24
- WAN: 203.0.113.0/24

---

# Routing

- Dynamic routing using OSPF
- All routers working in area 0
- Loopback interfaces advertised via OSPF

---

# Testing
Connectivity tested using ping command:
- LAN connection tests
- WAN reachability
- Users hosts ping
- OSPF neighbor verification
- Traceroute path validation

More details in "/tests/connection-tests.txt"

---

# Software
- Cisco Packet Tracer

---

# by Maciej Szukiel
