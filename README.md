# Network Penetration Testing Lab (Bettercap)
Detailed report with setup, commands, screenshots, and findings is available here:

[View Full Report](./Bettercap_Network_Penetration_Testing_Report.pdf)

## 📌 Project Overview
This project demonstrates how Man-in-the-Middle (MitM) attacks, ARP Spoofing, and SSL Stripping are conducted within a controlled virtual environment. Using **Bettercap** and **Kali Linux**, this lab evaluates network vulnerabilities and analyzes the behavior of secure vs. unsecure protocols.

## 🛠️ Tools & Technologies Used
* **Attacker OS:** Kali Linux
* **Victim OS:** Windows / Linux (Virtual Machines)
* **Hypervisor:** Oracle VirtualBox / VMware
* **Network Tool:** Bettercap
* **Traffic Analysis:** Wireshark

## 🚀 Scenarios Demonstrated
1. **Network Reconnaissance:** Discovering active hosts and mapping the network topology.
2. **ARP Spoofing:** Intercepting traffic between the gateway and target devices.
3. **SSL Stripping & Credential Harvesting:** Downgrading HTTPs traffic to HTTP on vulnerable sites to capture login credentials.
4. **Network Denial of Service (DoS):** Executing `arp.ban` to simulate a complete network disconnection for target devices.

## 🛡️ Security Countermeasures
* Implementing Dynamic ARP Inspection (DAI) on managed switches.
* Enforcing Strict Transport Security (HSTS) on websites.
* Utilizing End-to-End Encryption and secure VPNs on public networks.

## Key Findings
- Successfully performed ARP spoofing attack
- Intercepted HTTP traffic
- Demonstrated SSL stripping limitations on HSTS-enabled websites
- Captured network packets using Wireshark

---
*Note: This project was conducted strictly for educational and ethical hacking purposes in an isolated lab network.*
