# 🌐 PT Dreament Entertainment — Network Topology

A multi-floor enterprise network simulation built using Cisco Packet Tracer as a final project for the Computer Networks course at Universitas Amikom Yogyakarta.

The project simulates a corporate network for PT Dreament Entertainment, featuring VLAN-based network segmentation, inter-router routing, access control lists, and wireless connectivity across three floors.

## 📌 Project Overview

The network is designed to organize devices and departments across three floors of an office building. Each floor has its own network configuration, while routers connect the different networks to enable communication between departments.

The main goal of this project was to design, configure, and test a structured enterprise network using Cisco Packet Tracer.

## 🏢 Network Design

The simulated network consists of three floors:

- **Floor 1:** Operational, Finance, and Marketing departments.
- **Floor 2:** Production department.
- **Floor 3:** Management department.

Each floor contains network devices such as routers, switches, PCs, laptops, and wireless networking devices.

## ✨ Key Features

- **VLAN Segmentation** — Separates departments into different logical networks.
- **Inter-Router Routing** — Connects networks across multiple floors.
- **Router-on-a-Stick** — Uses router subinterfaces to provide inter-VLAN routing.
- **VTP Server and Client** — Distributes VLAN information between switches on the first floor.
- **Access Control Lists (ACLs)** — Applies rules to control traffic between selected networks.
- **Static Routing and RIP v2** — Configures routes for communication between routers.
- **NAT Configuration** — Implements network address translation for external network access.
- **Wireless Networking** — Configures wireless routers and Wi-Fi security for mobile devices.
- **IP Addressing and Subnetting** — Assigns IP addresses and subnet masks to devices and network interfaces.

## 🗂️ VLAN Configuration

| VLAN ID | Department | Network |
|---|---|---|
| VLAN 5 | Operations | `192.168.10.0/28` |
| VLAN 6 | Finance | `192.168.10.16/28` |
| VLAN 7 | Marketing | `192.168.10.32/28` |
| VLAN 10 | Production | `192.168.10.48/28` |
| VLAN 12 | Management | `192.168.10.64/28` |

## 🛠️ Tools and Technologies

- Cisco Packet Tracer
- Cisco IOS CLI
- VLAN and VTP
- RIP v2 and Static Routing
- ACL
- NAT
- IPv4 Addressing and Subnetting
- Wireless Networking

## 🧪 Testing and Troubleshooting

The network was tested through connectivity checks between PCs across the different floors. PC connectivity between floors was successfully established.

Wireless smartphone connectivity was not fully resolved during the project and remained an area for further troubleshooting.

This project provided practical experience in configuring network devices, diagnosing connectivity issues, and understanding how VLANs and routing affect communication across an enterprise network.

## 🚀 How to Open the Project

1. Download the `.pkt` file from this repository.
2. Install and open Cisco Packet Tracer.
3. Open the downloaded project file.
4. Inspect the network topology and device configurations.

## 🎓 Academic Background

This project was developed as a final examination project for the Computer Networks course during the 2024/2025 academic year at Universitas Amikom Yogyakarta.

## 👩‍💻 My Contribution

My primary contribution was designing the network topology and configuring the network devices in Cisco Packet Tracer, including routers, switches, VLANs, IP addressing, and routing.

The project was completed collaboratively as part of a university assignment.

---

**Project Type:** Computer Networking  
**Simulation Tool:** Cisco Packet Tracer  
**Network Design:** Three-floor enterprise network  
**Institution:** Universitas Amikom Yogyakarta
