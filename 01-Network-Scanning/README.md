# Network Scanning & Discovery

## Overview
This lab focuses on network discovery, port scanning,
and service identification using Nmap and Zenmap in
an authorized virtual laboratory environment.

## Tools & Technologies
- Kali Linux
- Nmap
- Virtual Machines

## Objectives
- Discover active hosts within a network.
- Identify open TCP and UDP ports.
- Detect running network services.
- Understand how network scanning supports
  security assessments.

## Methodology
1. Configured an isolated virtual lab environment.
2. Performed host discovery using Nmap.
3. Conducted TCP and UDP port scanning.
4. Examined open ports and running services.
5. Documented findings for security analysis.

## Skills Demonstrated
- Network Reconnaissance
- Host Discovery
- Port Scanning
- Service Identification
- Network Security Assessment
- Technical Documentation

## Security & Ethics
All scanning activities were performed in authorized
educational environments for learning purposes.

## Lab Evidence

### Nmap TCP SYN Scanning

Performed TCP SYN scans against an authorized virtual machine to identify open and closed ports.

The scans identified open services including FTP, SSH, Telnet, and HTTP.

![Nmap SYN Scan Results](evidence/IMG_6514.jpeg)

### Network Discovery and Host Identification

Performed a network discovery scan using Nmap to identify active hosts within the target subnet.

The scan identified 3 active hosts out of 256 IP addresses.

Created an IP address list (iplist.txt) for further network enumeration.

![Network Discovery Results](evidence/IMG_6518.jpeg)
