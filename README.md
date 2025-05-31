
# Nmap Network Port Scanning - Internship Task

This repository contains the results and findings of my local network scan using "Nmap", as part of my cybersecurity internship.

# What I Did

- Installed and used "Nmap" to scan open ports on my local IP (`192.168.31.155`)
- Performed a "TCP SYN Scan" using the command:
  
  nmap -sS -T4 192.168.31.155
  
- Identified open ports and researched the services running on them
- Analyzed potential security risks of those open ports
- Documented everything in the `report.md` file

# Files in This Repo

|      File Nam     |               Description                        |
|-------------------|--------------------------------------------------|
| `report.md`       | My report summarizing scan results and learnings |
| `scan_results.txt`|   Actual Nmap output showing open ports          |

# What I Learned

- How to scan a device for open ports using Nmap
- What common ports like 135, 139, and 445 are used for
- The importance of securing unnecessary open ports on a network
- Basic cybersecurity hygiene when connected to different networks

# Note

This scan was only run on my own machine in a safe and legal environment for learning purposes.
