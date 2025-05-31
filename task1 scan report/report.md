
# Cybersecurity Internship Task Report - Nmap Scan

Name: Sakshi Patil  
Task: Scan Local Network for Open Ports  
Tool Used: Nmap  
Date: 31st May 2025

---

# Tools I Used

Nmap – for scanning open ports on my device.
Wireshark – not used in this task, but I checked it out for future use.

---

# IP Address and Target Info

- My local IP: `192.168.31.155`
- I scanned only my own machine to test Nmap.
- This helped me understand what services are running on my laptop.

---

##  Nmap Command I Used


nmap -sS -T4 192.168.31.155


I used the `-sS` flag for a SYN scan and `-T4` to make the scan faster.

---

# Scan Results (Open Ports Found)

PORT    STATE SERVICE
135/tcp open  msrpc
139/tcp open  netbios-ssn
445/tcp open  microsoft-ds

These are common Windows ports. It means some file sharing and remote services are active.

---

# What I Learned

| Port | Service        |   What it Does         | Is It Risky? |
|------|----------------|------------------------|--------------|
| 135  | MSRPC          | Remote procedure calls |    Medium    |
| 139  | NetBIOS-SSN    | Windows file sharing   |    Medium    |
| 445  | Microsoft-DS   | SMB (file transfer)    |     High     |

- Port 445 is often targeted by malware like WannaCry.
- These services should be blocked if I'm on public Wi-Fi.

---

# My Suggestions

- I’ll keep my firewall on always.
- I’ll disable file sharing when not needed.
- I’ll continue learning how attackers misuse these ports.

---

# Files Attached

- `scan_results.txt`: Output of my real scan
- `report.md`: This summary report

---

Thanks for reading my report! 
