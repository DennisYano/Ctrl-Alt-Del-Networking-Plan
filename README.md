# Ctrl-Alt-Del Networking Plan

This project is from a networking assignment where I designed IP addressing schemes for a fictional company with two offices: Iqaluit (North) and Pelee (South). The goal was to calculate valid subnets using VLSM, assign IP ranges, determine broadcast addresses, and recommend routing protocols.

## Skills Demonstrated
- Subnetting & VLSM calculations for different host requirements
- IP address planning for multi-site LAN environments
- Private IP space selection (Class B + Class C)
- Understanding broadcast ranges & valid host ranges
- Routing protocol reasoning (RIP vs OSPF)

## South Office Example (/27)
Each subnet needed to support different host counts. A /27 mask supports 30 usable hosts per subnet.

Example subnets:
- 192.168.1.32/27
- 192.168.1.64/27
- 192.168.1.96/27
(see screenshot for sample table)

## North Office Example (/23)
A larger subnet mask was chosen to support higher host capacity while leaving room for growth.

## Why this matters in cybersecurity
SOC analysts frequently investigate:
- abnormal IP activity
- traffic crossing VLANs / subnets
- lateral movement detection

Understanding subnets helps determine if traffic is legitimate or not.

## Artifacts Included
- PDF/Docx writeup
- Sample subnet screenshot

## Author
Dennis Yanovski  
GitHub: https://github.com/DennisYano
