# Multi-Site Secure Network Architecture & Implementation Report
## Case Study: Alpha Logistics (Manchester & London Branch Offices)

## 📌 Executive Summary
This repository contains the comprehensive network architecture, engineering design, and security implementation report for **Alpha Logistics**, a multi-site enterprise topology connecting corporate offices across Manchester and London. 

The project demonstrates advanced competency in infrastructure deployment, scalable network design, dynamic routing, and network security hardening using industry-standard Cisco technology guidelines.

---

## 🛠️ Core Technical Specifications & Architecture

The infrastructure is engineered to handle enterprise-level data traffic, strict security compliance, and logical network segmentation across two primary geographic regions:

* **Routing & Switching Framework:** Dynamic routing deployed via **EIGRP (Enhanced Interior Gateway Routing Protocol)** for fast convergence and reliable inter-site WAN communication. Inter-VLAN routing is handled via a **Router-on-a-Stick** design topology.
* **Logical Network Segmentation:** Custom VLANS configured to segregate critical business divisions (Management, Staff, Warehousing, Guest, and Core IT Services).
* **IP Addressing Strategy:** Optimized **Classless Inter-Domain Routing (CIDR)** VLSM subnetting schemes to maximize address space efficiency and eliminate subnet waste.
* **Core Infrastructure Services:** Enterprise deployment of centralized DHCP pools, authoritative DNS routing, local corporate Web (HTTP/HTTPS) staging services, and dedicated Email protocols.
* **Security & Hardening Matrix:** Implementation of Router Security Base Configuration, boundary protection via Access Control Lists (ACLs), and secure enterprise Wireless Infrastructure (Staff Wi-Fi VLANs).

---

## 📂 Repository Contents

* `Enterprise-Network-Architecture-Design-Alpha-Logistics.pdf` - Full engineering report featuring topology schemas, detailed configuration logic, and comprehensive test documentation.

---

## 🔍 Verification & Test Validation
The implementation has been thoroughly validated inside a simulation environment to confirm full system uptime and connectivity. Proof-of-concept evidence within the main documentation verifies:
1.  **Inter-VLAN Communication:** Isolated traffic policies successfully passing across segmented local networks.
2.  **Inter-Site Connectivity:** Dynamic EIGRP WAN route verification showing 0% packet loss between Manchester and London.
3.  **Service Availability:** Real-time client verification for DHCP leases, DNS name resolution, web server rendering, and corporate email routing.

---

## 🔏 Academic & Professional Integrity Disclaimer
This repository contains architectural documentation for an enterprise network design simulation completed as part of my university coursework at Manchester Metropolitan University. The files are published here exclusively as a professional portfolio piece to showcase network engineering competency. Current students are advised to adhere to academic integrity guidelines; raw configuration or simulation files are kept private to prevent plagiarism.

***
💡 **Developed by Usman Akhter** * **GitHub Portfolio:** [UsmanAkhter-Cybersecurity](https://github.com/UsmanAkhter-Cybersecurity)
