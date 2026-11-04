# NETWORKWALKS-SAEED-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Cybersecurity Lab Environment Setup

Building an isolated virtual lab for penetration testing and ethical hacking practice.

## Lab Overview
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux[cite: 18]. The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly[cite: 18]. 

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing[cite: 18].

## Technical Specifications & Tools
* **Host Operating System:** Windows 10 / 11
* **Virtualization Software:** Oracle VM VirtualBox (v7.x)
* **Guest Operating System:** Kali Linux (2026.3)
* **Network Mode:** NAT Network / Host-Only Adapter (for isolated local testing)
* **Primary Tools Installed:** Nmap, Wireshark, Metasploit, Gobuster, Burp Suite

## Step-by-Step Implementation Summary
1. **Downloaded & Installed VirtualBox:** Installed the core hypervisor along with matching Extension Packs to resolve driver compatibility.
2. **Imported/Installed Kali Linux:** Deployed the official Kali Linux virtual machine image configured with 2GB+ RAM and dual processor cores.
3. **Configured Network & Storage:** Verified network adapters and allocated virtual hard disk storage (80 GB VDI).
4. **Tested Connectivity & Environment:** Booted the Kali Linux environment and verified package updates via terminal.

## Disclaimer
*These materials are for education and research purposes only[cite: 3]. Do not test or attack systems without explicit written permission[cite: 3]. Every action you take is your own responsibility[cite: 3].*
