# 🖥️ OS Hardening

SecuriSurf AI provides clear, actionable instructions to secure Windows and Linux systems.

## Windows OS Hardening
1. **Update Windows:** Keeps your system patched against known vulnerabilities.  
   Path: Settings → Update & Security → Windows Update → Check for updates  
2. **Enable Windows Firewall:** Protects against unauthorized access.  
   Path: Control Panel → System and Security → Windows Defender Firewall → Turn on  
3. **Enable BitLocker (Pro versions):** Encrypts your drive to prevent data theft.  
   Path: Control Panel → System and Security → BitLocker Drive Encryption  
4. **Disable Unnecessary Services:** Reduces attack surface.  
   Run `services.msc` → Right-click unneeded services → Disable  
5. **Use Local Account With Limited Privileges:** Prevents malware from having admin rights.  

## Linux OS Hardening (Ubuntu Example)
1. **Update and Upgrade Packages:** Keeps system secure with latest patches.
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```
2. **Enable Firewall (UFW):** Blocks unauthorized network traffic.
   ```bash
   sudo ufw enable
   sudo ufw status
   ```
3. **Disable Root Login via SSH:** Prevents brute-force attacks.
   Edit `/etc/ssh/sshd_config` → Set `PermitRootLogin no` → Restart SSH
4. **Install Fail2Ban:** Protects against repeated failed login attempts.
   ```bash
   sudo apt install fail2ban -y
   ```
5. **Check Open Ports:** Ensure only necessary ports are open.
   ```bash
   sudo netstat -tulpn
   ```

