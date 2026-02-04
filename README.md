# Enterprise Network Design – HQ & Branch (ROBO)

## 📌 Overview
This repository documents an enterprise-style network design covering a
Head Office (HQ) and a Remote Branch Office (ROBO).

The project focuses on **design-first networking**, where physical topology,
logical architecture, and IP addressing are carefully planned before deployment.

## 🎯 Objectives
- Build a scalable and resilient enterprise network
- Separate traffic using VLANs (LAN, Servers, VoIP, Wi-Fi, Guests, APs, Management)
- Implement high availability at the network edge
- Maintain clean, structured IP addressing
- Document decisions for easy troubleshooting and future growth

## 🏗 Architecture Summary
- Layer 3 core switching at HQ
- Dual edge routers with VRRP for gateway redundancy
- Dedicated transit subnets
- Centralized wireless using a WLC
- HQ and Branch using separate address spaces
- Voice-ready access design (data + voice VLANs)

## 🧱 Technologies & Concepts
- VLANs & 802.1Q Trunking
- VRRP (Gateway Redundancy)
- EtherChannel (LAG)
- Layer 3 Switching
- Centralized DHCP (Windows Server – planned)
- Wireless LAN Controller architecture

## 📂 Project Status
🚧 Work in progress  
Current focus: addressing scheme, VLAN design, and documentation.  
Logical diagrams and configs will follow.

## ✍️ Author
Lewis Mwita  
Enterprise Networking | Learning by Building

