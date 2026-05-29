# Enterprise IT Infrastructure & Cybersecurity Project

> A complete enterprise infrastructure simulation focused on networking, server deployment, penetration testing, ethical hacking, and security hardening.

---

# 📌 Overview

This project demonstrates the design, implementation, testing, and security validation of a complete enterprise IT infrastructure environment built entirely from scratch.

The environment simulates a real-world enterprise network where networking engineers, server administrators, penetration testers, and ethical hackers collaborate to deploy and secure enterprise services while validating resilience against cyberattacks.

The project included:

* Enterprise Network Architecture
* VLAN Segmentation & Routing
* Ubuntu Server Infrastructure
* Load Balancing & Web Hosting
* Penetration Testing Operations
* Ethical Hacking Simulations
* Security Hardening & Remediation

Unlike traditional infrastructure projects, this environment was actively tested through controlled attacks to evaluate the resilience of every infrastructure layer.

---

# 🎯 Project Objectives

* Build a scalable enterprise infrastructure
* Design secure VLAN-based network segmentation
* Deploy and harden Linux web servers
* Configure load balancing and high availability
* Perform penetration testing against live services
* Simulate real-world cyberattacks
* Identify vulnerabilities and apply mitigations
* Improve operational collaboration between infrastructure and security teams

---

# 🏗️ Infrastructure Architecture

## Network Architecture

* Base Network: `172.16.0.0/24`
* 3 VLAN segmented `/26` networks
* Cisco Catalyst 3560 Core Switch
* Juniper EX3200 Access Switch
* Layer 3 Switching
* DHCP Services
* ACL Security Policies
* EtherChannel (LACP)
* Rapid PVST+

## VLAN Structure

| VLAN    | Purpose        | Network         |
| ------- | -------------- | --------------- |
| VLAN 10 | Wired Users    | 172.16.0.0/26   |
| VLAN 20 | Wireless Users | 172.16.0.64/26  |
| VLAN 30 | Servers        | 172.16.0.128/26 |

---

# 🔌 Network Engineering

The networking infrastructure was designed to simulate enterprise-grade communication and segmentation.

## Implemented Technologies

* VLAN Architecture
* IP Subnetting
* DHCP Configuration
* EtherChannel
* Trunking
* Access Control Lists (ACLs)
* Rapid Spanning Tree Protocol (RSTP)
* Cisco Catalyst 3560 Configuration
* Juniper EX3200 Configuration

## Key Features

* LACP EtherChannel uplinks
* STP root bridge priority configuration
* DHCP relay configuration
* VLAN traffic isolation
* Trunk-based inter-switch communication
* ACL-based server protection

---

# 🖥️ Server Infrastructure

The server team deployed multiple Linux servers powering live web applications and load balancing systems.

## Infrastructure Components

* Ubuntu Server
* Nginx Web Server
* MySQL Database
* Reverse Proxy Load Balancers
* Static IP Configuration
* Nginx Upstream Balancing

## Deployed Services

### Web Server 1 — TerraFusion

* Ubuntu Server
* Nginx
* MySQL
* Static IP: `172.16.0.13`

### Web Server 2 — UniLink

* Ubuntu Server
* Nginx
* MySQL
* Backend Deployment
* PHP-FPM Integration

### Load Balancers

* Nginx Upstream Balancing
* Traffic Distribution
* Redundancy & Availability
* Static IP: `172.16.0.130`

---

# 🔐 Security Hardening

Security was integrated throughout the entire infrastructure deployment.

## Security Measures

* ACL Enforcement
* Server Hardening
* UFW Firewall Configuration
* VLAN Segmentation
* DHCP Exclusions
* STP Loop Prevention
* Database Isolation
* Traffic Filtering
* Access Restrictions

---

# 🔍 Penetration Testing

The penetration testing phase focused on identifying weaknesses in the deployed environment.

## Tools Used

* OWASP ZAP
* Nmap
* Kali Linux

## Operations Performed

* Reconnaissance
* Host Discovery
* Service Enumeration
* Vulnerability Scanning
* Exploitation Attempts
* Security Reporting

## Identified Vulnerabilities

* Clickjacking
* Stored XSS
* Reflected XSS
* Missing Security Headers
* Weak Session Security

---

# 🛡️ Ethical Hacking Operations

The ethical hacking team simulated real-world offensive attacks against the infrastructure.

## Tools Used

* Burp Suite
* Bettercap
* Wireshark
* SQLMap
* Gobuster
* Nikto
* Hping3
* Apache Benchmark (ab)

## Simulated Attacks

* DDoS / SYN Flood
* SQL Injection
* Session Hijacking
* Authentication Brute Force
* Directory Traversal
* ARP Spoofing
* Credential Attacks
* Stored XSS Exploitation

---

# ⚠️ Major Security Findings

## DDoS Vulnerability

* No rate limiting
* No SYN cookie protection
* Service exhaustion under high traffic

## SQL Injection

* Unsanitized input fields
* Broken access control
* Full order data exposure

## Stored XSS

* No output encoding
* Persistent client-side script execution

## Session Hijacking

* No HTTPS
* Missing Secure & HttpOnly cookie flags
* Session token interception possible

## Authentication Weaknesses

* Weak passwords
* No account lockout
* No brute-force protection

---

# ✅ Mitigations & Recommendations

* Enable HTTPS/TLS
* Implement rate limiting
* Configure SYN cookies
* Add WAF/CDN protection
* Use prepared SQL statements
* Apply input sanitization
* Add Content Security Policy (CSP)
* Enable Secure & HttpOnly cookie flags
* Implement account lockout policies
* Restrict sensitive directories and endpoints

---

# 📊 Technologies Used

## Networking

* Cisco Catalyst 3560
* Juniper EX3200
* VLANs
* STP
* EtherChannel
* ACLs
* DHCP

## Systems Administration

* Ubuntu Server
* Nginx
* MySQL
* PHP-FPM
* Linux Hardening

## Cybersecurity

* Kali Linux
* Nmap
* OWASP ZAP
* Burp Suite
* SQLMap
* Bettercap
* Wireshark
* Gobuster
* Nikto

---

# 👥 Team Structure

## 🔌 Network Engineering

* Youssef Hussein
* Malak Mostafa
* Dana Sameh
* Jomana Yasser

## 🖥️ Server Administration

* Menna Osama
* Aida Bahaa
* Saja Hany
* Malak Akram

## 🔍 Penetration Testing

* Shahd Mahmoud
* Ayah Youssef

## 🛡️ Ethical Hacking

* Youssef Ahmed
* Abanoub Takla
* Ahmed Shawki
* Adam
* Ahmed Sobhi
* Salma Yasser

---


---

# 📑 Project Presentation

Presentation PPT:
https://1drv.ms/p/c/8DE1764BB24BD95A/IQDADBKbAHDlS4tcAiuaL_sEAbOzVDqCYcEFc4LfUlTLG4U?e=eCbywU

---

# 🚀 Key Outcomes

* Successfully deployed a complete enterprise infrastructure
* Simulated real-world enterprise workflows
* Performed live offensive security testing
* Identified and mitigated major vulnerabilities
* Improved enterprise networking knowledge
* Applied practical cybersecurity methodologies
* Built scalable and resilient infrastructure systems

---

# 🏷️ Tags


<div class="pc-tags"><span>Enterprise Infrastructure</span><span>Network Engineering</span><span>Cisco Catalyst 3560</span><span>Juniper EX3200</span><span>VLANs</span><span>Subnetting</span><span>STP</span><span>EtherChannel</span><span>ACLs</span><span>Ubuntu Server</span><span>Nginx</span><span>MySQL</span><span>Penetration Testing</span><span>Ethical Hacking</span><span>Cybersecurity</span><span>OWASP ZAP</span><span>Nmap</span><span>Burp Suite</span></div>


---

<p align="center">
  <sub>Built collaboratively as a real-world enterprise infrastructure and cybersecurity simulation project.</sub>
</p>
