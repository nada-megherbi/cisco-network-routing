# 🌐 Cisco Inter-Router Subnet Routing Simulation

A computer networking project simulating communication between two distinct subnets interconnected through a multi-router topology using Cisco Packet Tracer.

## 🚀 Project Overview
This project demonstrates foundational networking principles, focusing on Layer 3 (Network layer) routing, IPv4 subnetting, and device configuration. Two routers are configured to route traffic seamlessly between separate local subnets, ensuring end-to-end host connectivity.

## 🛠️ Network Topology & Configuration
- **Topology:** 2 Routers, Switches, and End Hosts (PCs) distributed across two unique subnets.
- **Routing:** Static routing / Direct interface configuration to establish inter-subnet communication.
- **Tools:** Cisco Packet Tracer

### Subnetting Scheme (Example)
- **Subnet A:** `192.168.1.0/24` (Gateway: `192.168.1.1`)
- **Subnet B:** `192.168.2.0/24` (Gateway: `192.168.2.1`)
- **Inter-Router Link:** `10.0.0.0/30`

## ⚙️ Key Concepts Implemented
- IPv4 Subnet Mask calculation and host allocation
- Router interface configuration (`FastEthernet`, `GigabitEthernet`, `Serial`)
- Gateway setup for local area networks
- Verification of network connectivity using the `ping` utility and routing tables (`show ip route`)

## 📂 Repository Contents
- `network_topology.pkt`: The original Cisco Packet Tracer simulation file.
- `topology_screenshot.png`: Visual overview of the network layout and successful ping tests.

## ▶️ How to View
1. Download or clone this repository.
2. Open the `.pkt` file using **Cisco Packet Tracer**.
3. Inspect router CLI configurations or test packet delivery using simulation mode.
