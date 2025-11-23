# Elevate-Labs-Cyber_Internship_Task_5
Capturing and Analyzing Network Traffic Using Wireshark.

# CyberSecurity-Task5 - Capture and Analyze Network Traffic Using Wireshark.

**Name:** RAO JITENDRASINGH KAMLENDRASINGH
**Task:** Capturing and Analyzing Network Traffic Using Wireshark.
**Date:** 21-11-2025

## Objective  
The goal is to capture live network traffic using **Wireshark**, analyze different types of packets, identify protocols, and export the capture as a `.pcapng` file.

## Tools Used  
- Wireshark 

# Files in this repo
- `capture.pcapng` — Packets capturing report.
- `Packets_Capturing.mp4` - Screen recording of capturing.
- `Screenshots/` — screenshots of filtered packets
  - WS_Home.png
  - Packets_udp.png
  - Packets_tcp.png
  - Packets_icmp.png
  - Packets_http.png
  - Packets_dns.png
- `README.md` — this file


## 📑 Steps Performed

### Installed Wireshark
- Downloaded Wireshark from the official website and installed it with default settings.  
- Verified that **Npcap** was also installed (required for packet capturing).

### Started a Packet Capture
- Opened Wireshark  
- Selected the **active network interface** (Wi-Fi)  
- Clicked **Start Capturing Packets**  

### Generated Traffic
To produce packets for analysis:
- Opened a few websites  
- Ran `ping google.com` in terminal  
- Let traffic capture run for ~1 minute  

### Stopped the Capture
- Clicked the **red square (Stop)** button.  
- Saved the capture as `capture.pcapng`.

### Applied Filters
Used Wireshark filters to analyze specific protocols, for example:

- `http`
- `tcp`
- `udp`
- `dns`
- `icmp`

### Identified at Least 3 Protocols
Protocols found in the capture:
1. **DNS** – domain name resolution queries  
2. **TCP** – connection-oriented traffic  
3. **ICMP** – used for ping  
4. **HTTP** - if websites were opened  

### Exported the Capture
Went to:
- **File → Save As**
- Exported the file as `capture.pcap`  

### Summary of Findings
- I observed DNS queries when visiting websites.  
- TCP packets showed three-way handshake and data transmission.  
- ICMP packets were not visible during.  
- Filtering using protocol names made analysis easy.  
- Packet details helped identify IP addresses, ports, flags, and payloads.

## Objective
To perform a basic vulnerability scan on my personal computer using a free vulnerability scanning tool (Nessus Essentials or OpenVAS) and identify common security risks.


