# Cybersecurity Lab Environment Setup

Building an isolated virtual lab for penetration testing and ethical hacking practice.

## Lab Overview
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux[cite: 18]. The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly[cite: 18].

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing[cite: 18].

---

## Technical Specifications & Tools
* **Host Operating System:** Windows 10 / 11
* **Virtualization Software:** Oracle VM VirtualBox (v7.x)
* **Guest Operating System:** Kali Linux (2026.3)
* **Network Mode:** NAT Network / Host-Only Adapter (for isolated local testing)
* **Primary Tools Installed:** Nmap, Wireshark, Metasploit, Gobuster, Burp Suite

---

## Step-by-Step Implementation

### 1. VirtualBox Manager Setup
Configured and verified the virtualization hypervisor and ensured the virtual machine is successfully created and powered off/ready.

![VirtualBox Manager Setup](./Screenshot%202026-11-04%20125601.jpg)

### 2. Kali Linux Desktop Environment
Successfully booted the Kali Linux virtual machine into its XFCE desktop environment.

![Kali Linux Desktop](./VirtualBox_kali-linux-2026.3-virtualbox-amd64_04_11_2026_12_58_06.jpg)

---

## Disclaimer
*These materials are for education and research purposes only[cite: 3]. Do not test or attack systems without explicit written permission[cite: 3]. Every action you take is your own responsibility[cite: 3].*
