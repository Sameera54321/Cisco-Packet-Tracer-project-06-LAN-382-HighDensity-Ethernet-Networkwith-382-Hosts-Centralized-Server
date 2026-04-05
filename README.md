# Cisco-Packet-Tracer-project-06-LAN-382-HighDensity-Ethernet-Networkwith-382-Hosts-Centralized-Server
I’m pleased to share my latest networking project – LAN‑382 – a Cisco Packet Tracer simulation that models a high‑density local area network with 382 end devices (IP addresses 10.10.10.1 – 10.10.10.382), all connected through a single Cisco 2960‑24TT switch alongside a dedicated server (Server0).

![image alt](https://github.com/Sameera54321/-Cisco-Packet-Tracer-project-05-Inter-VLAN-Inter-Subnet-Routing-Lab-Server-PCs-Laptops-Two-Switches/blob/main/14.jpg?raw=true)

## 📌 Summary

### LAN‑382 is a high‑density Ethernet network simulation built with Cisco Packet Tracer. It consists of:

    1 x Cisco 2960‑24TT switch (24 ports, but extended via daisy‑chaining or multiple switches in the actual simulation)

    382 end hosts (IP addresses 10.10.10.1 through 10.10.10.382)

    1 x central server (Server0) providing services to all hosts

### The project explores:

    Switch operation under high MAC address table load

    Broadcast traffic analysis in a large flat LAN

    VLAN implementation to logically segment the network (even on a single switch)

    Basic server configuration (DHCP to automate IP assignment, DNS, HTTP)

    Port security and storm control to mitigate common issues

## ✨ Features

    ✅ 382 end hosts – each with a unique static or DHCP‑assigned IPv4 address

    ✅ Centralised server – provides DHCP, DNS, HTTP, and/or FTP services

    ✅ Cisco 2960 switch – configured with VLANs, port security, and Spanning‑Tree

    ✅ Broadcast domain analysis – observe behaviour with many hosts

    ✅ Scalability testing – MAC table size, switch CPU load (simulated)

    ✅ VLAN segmentation – split the 382 hosts into multiple logical networks (e.g., VLAN 10, 20, 30)

    ✅ Full Packet Tracer file (.pkt) – ready to open and experiment

    ✅ Documentation – IP addressing plan, VLAN mapping, switch configs, server setup

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x (or later)

    CLI – switch and server configuration

    (Optional) Python – if used to generate repetitive host configurations or IP lists

## 🤝 Contributing

Contributions are welcome! If you want to improve or extend the simulation:

    Fork the repository.

    Add new features – e.g., inter‑VLAN routing, wireless AP, redundant switches, or IPv6.

    Optimise switch configuration (storm control, port channels).

    Update the documentation with your changes.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
