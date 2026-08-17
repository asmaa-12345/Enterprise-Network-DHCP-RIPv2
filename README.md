# 🌐 Enterprise Network Simulation | DHCP & RIPv2

> A practical enterprise network simulation built with **Cisco Packet Tracer**, applying core **CCNA networking concepts** including IPv4 subnetting, DHCP, and RIPv2 dynamic routing.

---

## 📌 Project Overview

This project simulates an **enterprise network environment** where multiple branches are interconnected through routers.

The network was designed and configured to provide:

* 🔹 Automatic IP address assignment using **DHCP**
* 🔹 Dynamic routing between networks using **RIPv2**
* 🔹 Efficient IPv4 addressing using **Subnetting**
* 🔹 Communication between different enterprise branches
* 🔹 Network verification and troubleshooting

The project focuses on applying networking concepts in a practical environment rather than only studying them theoretically.

---

## 🏗️ Network Architecture

The topology consists of multiple routers, switches, and end devices representing different enterprise branches.

Each branch has its own local network, while the routers are responsible for forwarding traffic between different networks.

### Network Components

* 🖥️ End Devices
* 🔀 Cisco Switches
* 🌐 Cisco Routers
* 📡 DHCP Configuration
* 🔄 RIPv2 Dynamic Routing
* 📊 IPv4 Subnetting

---

## 🛠️ Technologies & Concepts

| Technology / Concept | Implementation          |
| -------------------- | ----------------------- |
| Cisco Packet Tracer  | Network Simulation      |
| IPv4                 | Network Addressing      |
| Subnetting           | Network Segmentation    |
| DHCP                 | Automatic IP Assignment |
| RIPv2                | Dynamic Routing         |
| Cisco IOS            | Device Configuration    |
| Ping                 | Connectivity Testing    |
| Routing Table        | Route Verification      |

---

## ⚙️ Configuration

### 🔹 IPv4 Subnetting

The network was divided into multiple subnets to provide separate networks for the different branches.

Subnetting was used to organize the network and efficiently allocate IP addresses.

### 🔹 DHCP

DHCP was configured to automatically provide end devices with:

* IP Address
* Subnet Mask
* Default Gateway

This eliminates the need to manually configure each end device.

### 🔹 RIPv2

RIPv2 was configured on the routers to dynamically exchange routing information between the different networks.

This allows routers to automatically learn remote networks and select available routes.

---

## 🧪 Network Verification

After completing the configuration, the network was tested to ensure proper connectivity and routing.

### Useful Cisco IOS Commands

```bash
show ip interface brief
show ip route
show ip protocols
```

### Connectivity Testing

```bash
ping <destination-ip>
```

These tests were used to verify:

* ✅ Interface status
* ✅ IP addressing
* ✅ DHCP operation
* ✅ RIPv2 routes
* ✅ Communication between branches
* ✅ End-to-end connectivity

---

## 📷 Network Topology

![image alt](https://github.com/asmaa-12345/Enterprise-Network-DHCP-RIPv2/commit/cea60566287a8f6c4b81c9d3d795ec1c91968650#diff-94bbf41d50e09c2dd4b661767acd4009cca4e6b9ac3696d18c0ab8911635f50f)

---

## 📁 Project Files

```text
D/
│
├── README.md
├── Enterprise-Network-DHCP-RIPv2.pkt
│
└── images/
    └── topology.png
```

### Files Description

**`Enterprise-Network-DHCP-RIPv2.pkt`**
Cisco Packet Tracer project containing the complete network topology and configuration.

**`images/topology.png`**
Network topology diagram used to visualize the enterprise network.

---

## 🎯 Learning Objectives

Through this project, I practiced and applied:

* IPv4 addressing
* Subnetting
* DHCP configuration
* RIPv2 dynamic routing
* Router configuration
* Switch configuration
* Network troubleshooting
* Connectivity verification
* Cisco IOS commands

---

## 💡 Key Takeaway

This project helped me move from **theoretical CCNA concepts to practical network implementation**, giving me hands-on experience with designing, configuring, and troubleshooting a multi-network enterprise environment.

---

## 👩‍💻 Author

### **Asmaa Tarek Elsayed Elgaml**

🎓 Faculty of Computers and Information – Menofia University

💻 **Networking & Cybersecurity**

📚 **CCNA | Network Security**

---

⭐ *This project was created as part of my practical networking and CCNA learning journey.*
