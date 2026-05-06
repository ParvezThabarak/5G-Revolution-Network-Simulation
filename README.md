# 5G Revolution Network Simulation using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and simulation of a **5G Cellular Communication Network** using Cisco Packet Tracer.

The simulation represents a real-world telecom infrastructure where multiple service providers such as **BSNL** and **Jio** provide connectivity to users through:

- Cell Towers
- Central Office Servers
- Routers
- Smartphones
- Internet Servers

The project showcases:

- 5G cellular network architecture
- Static routing
- DHCP configuration
- Wireless communication
- Internet connectivity
- End-to-end communication testing

---

# 🚀 Features

- 📡 Multi-provider 5G network simulation
- 🗼 Cell tower communication
- 🌐 Internet connectivity through core router
- 🔀 Static routing between multiple networks
- 📶 DHCP-based IP allocation
- 🧪 Ping and traceroute testing
- 📊 Network performance evaluation

---

# 🛠 Technologies Used

- Cisco Packet Tracer
- Networking Fundamentals
- Static Routing
- DHCP
- IP Addressing
- Wireless Networking

---

# 🏗 Network Architecture

The network consists of:

## Devices Used

- 3 Routers
- 2 Central Office Servers
- Multiple Cell Towers
- Smartphones
- Switch
- Internet Server (Google.com)

## Telecom Providers

- BSNL
- Jio

---

# 🌐 Network Topology

The topology simulates a real-world telecom network where:

1. Smartphones connect wirelessly to nearby cell towers
2. Cell towers communicate with Central Office Servers
3. CO Servers connect to routers
4. Routers exchange traffic through static routing
5. Core Router provides internet access

---

# 🧾 IP Addressing Scheme

## Base Network

```text
192.168.0.0/22
```

## Subnets

| Network | Subnet |
|----------|----------|
| BSNL Network | 192.168.10.0/24 |
| Jio Network | 192.168.20.0/24 |
| Google LAN | 192.168.30.0/24 |

---

# ⚙ Routing Configuration

Static routing is configured on all routers to enable communication between different networks.

## Example Static Route

```bash
ip route 192.168.20.0 255.255.255.0 10.0.0.2
```

---

# 📱 DHCP Configuration

Smartphones dynamically obtain IP addresses from their respective Central Office Servers using DHCP.

This simulates real-world telecom subscriber connectivity.

---

# 🧪 Testing & Validation

The network was tested using:

- ✅ Ping Tests
- ✅ Router-to-Router Communication
- ✅ Router-to-Server Communication
- ✅ Traceroute Analysis
- ✅ End-to-End Connectivity Verification

All devices successfully communicated across networks with 100% ping success rate.

---

# 📊 Results

The simulation successfully demonstrated:

- Reliable communication between telecom providers
- Proper routing between multiple networks
- Dynamic IP allocation
- Internet connectivity
- Low latency communication

---

# 📂 Project Structure

```text
5G-Revolution-Network-Simulation/
│
├── 5G_Network_Simulation.pkt
├── 5G_Revolution_Report.pdf
├── README.md
└── screenshots/
```

---

# ▶ How to Run the Project

1. Install Cisco Packet Tracer
2. Open the `.pkt` file
3. Start Simulation Mode
4. Use:
   - `ping`
   - `tracert`
5. Verify connectivity between devices

---

# 📸 Screenshots

## Logical Topology

```md
Add topology screenshot here
```

## Ping Test

```md
Add ping result screenshot here
```

## Traceroute Result

```md
Add traceroute screenshot here
```

---

# 🎯 Learning Outcomes

This project helped in understanding:

- 5G network infrastructure
- Router and switch configuration
- DHCP implementation
- Static routing
- Wireless networking concepts
- Network troubleshooting

---

# 🔮 Future Enhancements

Possible improvements include:

- OSPF/RIP Dynamic Routing
- IPv6 Support
- Network Security
- QoS Implementation
- Network Slicing
- IoT Integration

---

# 👨‍💻 Authors

- Rachamadugu Karthik Babu
- Anirudh Varma Alluri
- Vavilathota Parvez Thabarak

Department of Networking and Communications  
SRM Institute of Science and Technology

---

# 📚 Reference

Cisco Networking Academy – Introduction to Networks (Version 7.0)

---

# ⭐ Acknowledgement

This project was developed as part of the Computer Networks course to understand modern 5G communication infrastructure using practical simulation in Cisco Packet Tracer.
