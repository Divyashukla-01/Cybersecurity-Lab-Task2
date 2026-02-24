# Cybersecurity-Lab-Task2
Hands-on network security lab project demonstrating reconnaissance, port &amp; service scanning, vulnerability assessment (Nessus), packet analysis (Wireshark), and firewall configuration using Kali Linux and Metasploitable.

##  Overview
This project demonstrates practical implementation of network reconnaissance, port and service scanning, vulnerability assessment, packet analysis, and firewall configuration using Kali Linux and Metasploitable in a controlled lab environment.

The complete report with screenshots is included in the REPORT folder.

---

##  Lab Environment

- Attacker Machine: Kali Linux
- Target Machine: Metasploitable 2
- Network: VirtualBox Host-Only
- Tools Used:
  - Nmap
  - Nessus
  - Wireshark
  - hping3
  - iptables

---

#  Project Implementation

## 1️ Reconnaissance
- IP identification
- Whois lookup
- DNS lookup
- Ping sweep
- Basic Nmap scan

## 2️ Port & Service Scanning
- TCP SYN Scan
- UDP Scan
- Service Version Detection
- OS Detection
- Aggressive Scan

## 3️ Vulnerability Assessment
- Nessus Basic Network Scan
- Severity-based analysis (Critical/High/Medium/Low)

## 4️ Packet Analysis
- HTTP traffic capture
- DNS query analysis
- TCP three-way handshake
- FTP plaintext credential extraction
- SYN flood simulation

## 5️ Firewall Configuration
- Blocking FTP port (21) using iptables
- Verification using Nmap

---

#  Key Security Observations

- Multiple open ports increase attack surface.
- Outdated services introduce critical vulnerabilities.
- FTP transmits credentials in plaintext.
- Firewall rules reduce system exposure.

---

# Report

The detailed lab report with screenshots is available here:

`REPORT/Network_Security_Report.pdf`

---

##  Author
Divya Shukla  
B.Tech – Information Technology  
Cybersecurity Practical Lab Project
