# 📡 Network Security

SecuriSurf AI helps users secure home and small office networks with clear steps.

## Home Network Security
1. **Change Default Router Credentials:** Always set a strong admin username and password.
2. **Update Router Firmware:** Fixes known security vulnerabilities.
3. **Enable WPA3 or WPA2 Encryption:** Never use WEP.
4. **Disable WPS and UPnP:** Prevents unauthorized automatic connections.
5. **Use a Guest Network:** Keep IoT devices and visitor devices isolated.
6. **Change SSID Name:** Avoid using your name or personal info.
7. **Enable Router Firewall:** Adds an extra layer of network protection.

## Small Office / Beginner IT Network Security
1. **Segment Networks:** Separate servers, workstations, and guest networks to reduce exposure.
2. **Deploy Basic IDS/IPS:** Use Snort or Suricata for intrusion detection.
3. **Enable DHCP Logging:** Helps track all connected devices.
4. **Regular Network Scans:** Detect unknown devices or open ports using:
   ```bash
   nmap -sn 192.168.1.0/24
   ```
5. **Restrict Remote Management:** Only allow access from trusted IPs.
6. **Use VPN for Remote Access:** Encrypts traffic and prevents eavesdropping.
