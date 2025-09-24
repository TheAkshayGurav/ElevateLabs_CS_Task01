# ElevateLabs_CS_Task01
Scan Your Local Network for Open Ports
# Local Network Port Scan

## 📌 Objective
Discover open ports and services running on devices in the local network to understand network exposure and potential risks.

## 🛠 Tools Used
- [Nmap](https://nmap.org/) — network scanning tool  


## 🚀 Steps Performed
1. Installed Nmap (and Wireshark optionally).
2. Identified local IP range (e.g., `192.168.1.0/24`).
3. Performed TCP SYN scan:  
   ```bash
   sudo nmap -sS 192.168.1.0/24

  ** Performed service/version and OS detection:**

sudo nmap -sS -sV -O 192.168.1.0/24
Captured packets of specific hosts with tcpdump.

Identified potential risks from open ports and documented remediation steps.
