# Network Simulation Project: DNS, OSPF, and HTTP 🌐🖧

This project demonstrates the design and implementation of a multi-segment computer network in Cisco Packet Tracer, showcasing core networking protocols: **DNS**, **OSPF**, and **HTTP**.

---

## 📄 Project Description

This simulation features a network topology with:
- **15 Hosts**
- **5 Routers**
- **4 Switches**
- **3 Servers** (including dedicated DNS and HTTP servers)

Key protocols and technologies:
- **OSPF (Open Shortest Path First):** Dynamic, link-state routing across all routers for optimal path selection and robust connectivity.
- **DNS (Domain Name System):** Domain name resolution, enabling clients to access web services using user-friendly URLs.
- **HTTP (Hypertext Transfer Protocol):** Web server hosting and client access to web pages.

The network employs both classful (A, B, C) and classless IP addressing, demonstrating subnetting and flexible IP allocation.

---

## 🏗️ Topology Overview

- **Routers:** Configured with OSPF for dynamic routing.
- **Servers:** DNS server for name resolution, HTTP server for web content.
- **Clients:** Access web pages via domain names, validating DNS and HTTP integration.
- **Switches:** Provide LAN connectivity for hosts in each segment.

---

## 🧪 Key Connectivity Tests

- Accessing a web page from a client PC to the web server using a domain name (DNS + HTTP).
- Verifying OSPF routing table convergence and optimal path selection.
- Analyzing Ethernet frame encapsulation and routing table entries across devices.

---

## ⚙️ Technologies Used

- **Cisco Packet Tracer** (simulation environment)
- **OSPF** (dynamic routing protocol)
- **DNS** (domain name resolution)
- **HTTP** (web server/client communication)
- **Ethernet** (LAN connectivity)
- **IP Subnetting** (classful and classless addressing)

---

## 🚀 How to Use

1. **Open the project file in Cisco Packet Tracer.**
2. **Review device configurations:** routers (OSPF), servers (DNS/HTTP), hosts.
3. **Test connectivity:** 
   - Ping between hosts.
   - Access the web server from a client using a domain name.
4. **Analyze routing tables and encapsulation:** Use simulation mode for packet flow.

---

## 🙌 Acknowledgments

- Inspired by practical networking scenarios and protocol integration.
- Built for academic demonstration and hands-on learning.

---

> _For questions or contributions, feel free to open an issue or pull request!_
