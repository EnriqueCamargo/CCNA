# 🌐 CCNA Certification & Networking Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-blue?style=for-the-badge&logo=cisco" alt="Status">
  <img src="https://img.shields.io/badge/Focus-Routing%2C%20Switching%2C%20Security-orange?style=for-the-badge&logo=networkx" alt="Focus">
  <img src="https://img.shields.io/badge/Platform-Cisco%20Packet%20Tracer-green?style=for-the-badge&logo=cisco" alt="Platform">
</p>

---

## 🎯 Overview

Welcome to my **CCNA (Cisco Certified Network Associate)** repository. This space documents my hands-on journey, network topologies, configuration scripts, and structured labs as I master core networking principles, enterprise routing, modern switching, security fundamentals, and automation.

The primary goal of this repository is to bridge theoretical knowledge with practical, real-world implementations using **Cisco Packet Tracer**. Every lab includes its corresponding `.pka` simulation file along with a detailed Markdown documentation breakdown.

---

## 📚 Roadmap & Core Topics Covered

This repository is organized into modular directories aligned with the official Cisco CCNA exam blueprint:

### 1️⃣ Network Fundamentals
* Basic router and switch CLI navigation (`IOS`).
* Interface, cabling, and TCP/IP vs. OSI model analysis.
* IPv4 and IPv6 addressing, subnetting, and VLSM design.

### 2️⃣ LAN Switching Technologies
* VLANs (Virtual Local Area Networks) and trunking (`802.1Q`).
* Inter-VLAN routing (Router-on-a-Stick and Layer 3 switches).
* Spanning Tree Protocol (`STP`, `RSTP`) and EtherChannel link aggregation.

### 3️⃣ Routing Technologies
* Static routing (IPv4 and IPv6, floating static routes).
* Dynamic routing protocols: **OSPFv2** (single-area and multi-area).
* First Hop Redundancy Protocols (`HRP`, `HSRP`).

### 4️⃣ IP Services & Security Fundamentals
* Network Address Translation (`NAT`: Static, Dynamic, and PAT/Overload).
* DHCP configuration (Server, Relay Agents, and Client setups).
* Access Control Lists (`ACLs`: Standard and Extended for traffic filtering).
* Device security: Port security, SSH hardening, and password management.

### 5️⃣ Programmability & Automation (Introduction)
* Basic concepts of Software-Defined Networking (`SDN`).
* Controller-based architectures and API-driven infrastructure automation.

---

## 📂 Repository Structure

```text
ccna-labs/
│
├── 01-network-fundamentals/
│   ├── lab-01-basic-lan-ping/
│   │   ├── topologia.pka
│   │   └── README.md
│   └── ...
├── 02-switching-vlans/
├── 03-routing-ospf/
├── 04-ip-services-security/
└── README.md
