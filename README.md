# Task 2: Network Security & Scanning

ApexPlanet Cybersecurity & Ethical Hacking Internship, by Rupashi Sethi.

## About
In this task I practised reconnaissance, port scanning and vulnerability scanning on my own private lab. Everything was tested only inside this lab.

## Lab
| Item | Details |
|---|---|
| Attacker | Kali Linux (VirtualBox) |
| Target | Metasploitable2, 192.168.56.102 |
| Network | Host-Only (private) |
| Tools | Whois, Nslookup, Nmap, Nessus Essentials |

## What I did
| Part | Work |
|---|---|
| Recon | Whois and Nslookup on example.com, ping test, ping sweep |
| Nmap | TCP scan with service versions, UDP scan |
| Vulnerability scan | Nessus Basic Network Scan (used instead of OpenVAS, which did not run in my lab) |

## Key results
- 23 open TCP ports and 2 open UDP ports on the target
- Nessus found 7 critical, 4 high, 22 medium, 8 low and 96 info results
- Main problems: old software, plain-text services (telnet, FTP), weak VNC password

## Files
- Task2_Full_Report.pdf : full report with analysis
- recon/ : whois, nslookup and ping screenshots
- nmap/ : UDP and service version scans
- nessus/ : scan details, hosts, vulnerabilities, remediations

## Disclaimer
All activities were done on my own isolated lab for learning only.
