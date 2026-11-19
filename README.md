# CCNA IPv4 & IPv6 VLSM Subnetting Lab

## 📌 Project Overview

This project is a Cisco Packet Tracer networking lab designed to practice fundamental CCNA networking concepts.

The lab focuses on IPv4 VLSM subnetting, IPv6 subnetting, IP address allocation, and network device configuration.

## 🎯 Objectives

- Perform IPv4 VLSM subnetting.
- Calculate network and broadcast addresses.
- Assign IP addresses to network devices.
- Design IPv6 `/64` subnets.
- Configure routers and switches.
- Understand LAN network architecture.
- Practice practical CCNA networking concepts.

## 🌐 Network Requirements

**IPv4 Network:** `172.16.0.0/20`

**IPv6 Network:** `2001:211:DAC::/48`

The network consists of two LANs:

| LAN | Required Hosts |
|---|---:|
| User LAN | 520 |
| Server LAN | 12 |

## 🧮 IPv4 Addressing Plan

### User LAN

| Device / Information | IPv4 Address |
|---|---|
| Network Address | `172.16.0.0/22` |
| Subnet Mask | `255.255.252.0` |
| Broadcast Address | `172.16.3.255` |
| PC1 | `172.16.0.1` |
| PC2 | `172.16.1.4` |
| Printer | `172.16.2.3` |
| User LAN Switch | `172.16.3.253` |
| Gateway | `172.16.3.254` |

### Server LAN

| Device / Information | IPv4 Address |
|---|---|
| Network Address | `172.16.8.96/28` |
| Subnet Mask | `255.255.255.240` |
| Broadcast Address | `172.16.8.111` |
| Web Server 1 | `172.16.8.97` |
| Web Server 2 | `172.16.8.98` |
| DNS & TFTP Server | `172.16.8.99` |
| Server LAN Switch | `172.16.8.109` |
| Gateway | `172.16.8.110` |

## 🌍 IPv6 Addressing Plan

### User LAN — 11th Subnet

**Network Prefix:** `2001:211:DAC:A::/64`

| Device | IPv6 Address |
|---|---|
| Gateway | `2001:211:DAC:A::1/64` |
| PC1 | `2001:211:DAC:A::2/64` |
| PC2 | `2001:211:DAC:A::3/64` |
| Printer | `2001:211:DAC:A::4/64` |

### Server LAN — 15th Subnet

**Network Prefix:** `2001:211:DAC:E::/64`

| Device | IPv6 Address |
|---|---|
| Gateway | `2001:211:DAC:E::1/64` |
| Web Server 1 | `2001:211:DAC:E::2/64` |
| Web Server 2 | `2001:211:DAC:E::3/64` |
| DNS & TFTP Server | `2001:211:DAC:E::4/64` |

## 🛠️ Technologies & Tools

- Cisco Packet Tracer
- IPv4 Subnetting
- VLSM
- IPv6 Subnetting
- Router Configuration
- Switch Configuration
- LAN Networking

## 📂 Project Files

- `CCNA-VLSM-Lab.pkt` — Cisco Packet Tracer project file
- `README.md` — Project documentation
- `Screenshots/` — Network topology and configuration screenshots

*Note: Add the Packet Tracer file and screenshots to the repository after completing the lab.*

## 📚 Learning Outcomes

Through this project, I practiced:

- IPv4 VLSM subnet calculation.
- IPv6 subnet identification.
- Host IP address allocation.
- Network and broadcast address calculation.
- Gateway and switch management IP assignment.
- Basic network planning and documentation.

## 👨‍💻 Author

**Networking & CCNA Lab Practice**

This project is part of my hands-on learning journey in Computer Networking and Cisco CCNA.

---

⭐ If you find this project useful, feel free to explore the repository.
