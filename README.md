# Multi-Site Secure Network Architecture & Implementation Report
**Case Study:** Alpha Logistics (Manchester & London Branch Offices)

## 📌 Executive Summary
This repository contains the network architecture layout and implementation report for Alpha Logistics, a multi-site enterprise topology connecting corporate offices between Manchester and London. 

I designed this project to simulate a scalable corporate network, focusing on dynamic routing, logical network segmentation, and foundational boundary security using Cisco design guidelines.

## 🛠️ Technical Specifications & Topology

The infrastructure is built to handle data traffic, security compliance, and network segmentation across two geographic branch locations:

* **Routing & Switching:** Dynamic routing deployed via EIGRP for fast convergence and inter-site WAN communication. Inter-VLAN routing is handled using a Router-on-a-Stick topology.
* **Network Segmentation:** Custom VLANs configured to segregate business divisions, including Management, Staff, Warehousing, Guests, and Core IT Services.
* **IP Addressing:** Optimized Classless Inter-Domain Routing (CIDR) and VLSM subnetting schemes to maximize address space efficiency.
* **Core Services:** Centralized DHCP pools, authoritative DNS routing, local corporate Web staging services (HTTP/HTTPS), and dedicated Email protocols.
* **Security & Hardening:** Applied router baseline security, boundary protection using Access Control Lists (ACLs), and secure enterprise Wireless (WPA2/WPA3) infrastructure for Staff Wi-Fi.

## 📂 Repository Contents
* **Enterprise-Network-Architecture-Design-Alpha-Logistics.pdf:** Full engineering report featuring network topology diagrams, configuration logic, and test documentation.

## 🔍 Verification & Testing
The implementation was fully validated inside a simulation environment to confirm connectivity and uptime:
* **Inter-VLAN Communication:** Verified that isolated traffic policies successfully pass across segmented local networks.
* **Inter-Site Connectivity:** Dynamic EIGRP WAN route verification showing 0% packet loss between the Manchester and London routers.
* **Service Availability:** Client verification for DHCP leases, DNS name resolution, web server rendering, and corporate email routing.

## 🔏 Academic Disclaimer
This repository contains architectural documentation for an enterprise network design simulation completed as part of my coursework at Manchester Metropolitan University. The files are published here exclusively as a portfolio piece to showcase network engineering skills. 
*(Note: Raw configuration and simulation files are kept private to protect academic integrity).*

---
**Developed by Usman Akhter** | [GitHub Portfolio](https://github.com/UsmanAkhter-Cybersecurity)
