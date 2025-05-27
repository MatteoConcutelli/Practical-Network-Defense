# Practical-Network-Defense Assignments

Welcome to the repository for our ACME Network Security assignments, completed as part of our coursework at Sapienza University of Rome. These assignments demonstrate our hands-on experience with firewall configurations, VPN setup, and secure network design using OPNsense.

## 🛡️ Team Info

**Team Name:** *Guardians of the Gateway*
**Team Number:** 19

**Team Members:**

* Simone Ciferri
* Matteo Concutelli
* Giorgio Pesce

---

## 📄 Assignment Reports

### ✅ Assignment 1 - OPNsense Firewall Configuration

This report documents the configuration of firewall rules in an enterprise network environment segmented into DMZ, Clients, External Services, and Servers. Key highlights include:

* Implementation of the **least privilege** principle
* Secure access to internal services (DNS, Proxy, Syslog, Greenbone)
* HTTP/HTTPS service exposure from the DMZ to the Internet
* Use of **NAT** and **port forwarding**
* ICMP filtering, traceroute policies, and final remarks on network segmentation

---

### ✅ Assignment 2 - VPN and IPSec Tunnels

In this report, we expanded the ACME network security with VPN solutions. Major sections include:

* Setup of a **Certificate Authority** and server/client certificates
* Configuration of an **OpenVPN Road Warrior** setup with strict access policies for different user roles (Operators vs Employees)
* Preventing **VPN access restrictions bypass**
* Deployment of an **IPSec tunnel** between firewalls, including testing and validation of encrypted traffic
* Granular **firewall rule configuration** to secure inter-network communication

---

## 🔐 Technologies Used

* OPNsense Firewall & Routing Platform
* OpenVPN
* IPsec
* Linux (Kali Linux for testing and simulation)
* Network services: DNS, Proxy (Squid), Syslog, Graylog

## 🧪 Testing

Each configuration has been thoroughly tested via:

* Host and traceroute commands
* VPN connection trials with authentication
* Log analysis on both OpenVPN and IPsec tunnels

---

> *This repository is part of an academic project and does not represent a production-ready environment.*
