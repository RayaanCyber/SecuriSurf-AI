# 🏠 Home Lab Setup

SecuriSurf AI helps you build a **safe and practical home lab** for learning cybersecurity without risking your main devices or network.

---

## 1. Introduction
A home lab allows you to **practice IT and cybersecurity skills safely**.  
Benefits include:
- Hands-on experience with real systems
- Safe environment for learning network and system hardening
- Building projects for your resume or portfolio

---

## 2. Basic Home Lab Setup (Beginner-Friendly)
1. **Install a Virtualization Tool**
   - [VirtualBox](https://www.virtualbox.org/) (Free)
   - [VMware Workstation Player](https://www.vmware.com/products/workstation-player.html) (Free for personal use)

2. **Create Virtual Machines (VMs)**
   Recommended setup:
   - **Ubuntu Linux** (Main practice environment for security tools)
   - **Windows 10/11** (Practice OS hardening and malware defense)
   - **Optional:** **Kali Linux** (For ethical hacking and penetration testing)

3. **Allocate Resources**
   - 2 CPU cores and 2-4GB RAM per VM (adjust to your PC specs)
   - 20-40GB storage per VM

---

## 3. Networking in Your Lab
- **Isolated Host-Only Network:** Keeps lab traffic off your home Wi-Fi.
- **NAT Network (Optional):** Only use for downloading updates.
- Avoid connecting test VMs to your main network unless necessary.

---

## 4. Essential Security Tools to Install
1. **Wireshark** – Network packet analysis
2. **Nmap** – Network scanning and reconnaissance
3. **Fail2Ban / UFW** – Linux protection tools
4. **Metasploitable** – A deliberately vulnerable VM for safe testing

Install with commands (Linux example):
```bash
sudo apt update && sudo apt install nmap wireshark -y
```

---

## 5. Practice Exercises
- Scan your lab VMs with `nmap` to identify open ports
- Capture network traffic with Wireshark and analyze protocols
- Harden Windows: Enable firewall, disable unnecessary services
- Test Linux security: Install Fail2Ban and observe blocked attacks

Take screenshots and notes to **document your progress**—this builds your cybersecurity portfolio.

---

## 6. Safety Tips
1. Keep VMs **isolated** from your home network unless updating.
2. **Never test malware** on your main PC or active network.
3. Use **VM snapshots** to revert to a safe state if something breaks.

---

With this lab, you’ll be ready to **practice real-world cybersecurity skills** while staying safe!  
