# ?? College Campus LAN Network – Cisco Packet Tracer & IOS

A comprehensive **Campus Area Network (CAN)** simulation designed in **Cisco Packet Tracer**, demonstrating multi-building enterprise architecture, VLAN segmentation, inter-VLAN routing, DHCP, DNS, and wireless connectivity.

---

## ?? Walkthrough Video
The repository includes a full walkthrough simulation:
- **Video File:** \demo.mp4\ (Full screen walkthrough and packet simulation)

---

## ??? Network Architecture & Design

| Zone / Building | Role & Connected Devices | VLAN ID |
|---|---|---|
| **Admin Block** | Administrative PCs, High-Security Printers, Local Servers | VLAN 10 |
| **Academic Block** | Faculty Systems, Classrooms, Lab Workstations | VLAN 20 |
| **Library** | Student Catalog PCs, Digital Access Points | VLAN 30 |
| **Hostel Block** | Student Wi-Fi APs, Residential Devices | VLAN 40 |
| **Server Farm** | Core Web Server, DNS Server, Central DHCP Pool | VLAN 99 |

---

## ?? Features Implemented
- ? **Multi-Layer Switching (L2/L3)** — Core, distribution, and access layer hierarchy.
- ? **VLAN Segmentation** — Strict isolation between administration, academics, and student traffic.
- ? **Inter-VLAN Routing** — High-speed routing across subnets with router sub-interfaces / SVI.
- ? **Dynamic IP Addressing** — Centralized DHCP pools for automated client provisioning.
- ? **Domain Name System (DNS)** — Local intranet hostname resolution.
- ? **Wireless Access Points** — WPA2-secured wireless coverage for hostels and library.
- ? **Spanning Tree Protocol (STP)** — Loop prevention and redundant link failover.
- ? **End-to-End ICMP Testing** — Verified packet routing and zero-loss connectivity.

---

## ?? Repository Contents

| File / Folder | Description |
|---|---|
| \project.pkt\ | Primary full-scale campus network topology |
| \ssignment.pkt\ | Modular lab / assignment topology |
| \College_Campus_LAN_Network_PRO_3D.pptx\ | Complete 3D architecture slides and presentation |
| \demo.mp4\ | Recorded live demonstration of the network |
| \screenshots/\ | Topology maps and configuration evidence |

---

## ?? How to Run the Simulation

1. Install **[Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)** (v8.0+ or v9.0 recommended).
2. Clone this repository:
   \\\ash
   git clone https://github.com/ArnabHalder-CS/campus-lan-network.git
   \\\
3. Double-click \project.pkt\ to launch the simulation.
4. Toggle to **Simulation Mode** (bottom right) or use the **Add Simple PDU (P)** tool to inspect packet delivery between different VLANs.

---

## ????? Author
**Arnab Halder**  
GitHub: [@ArnabHalder-CS](https://github.com/ArnabHalder-CS)
