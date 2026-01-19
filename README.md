# Wireshark Network Analysis – Task 3

## 📌 Overview
This repository contains a detailed Wireshark network traffic analysis performed as part of a cybersecurity learning task. The objective was to understand basic networking protocols, capture live traffic, apply filters, and analyze encrypted vs plain-text communication.

## 🛠 Tools Used
- Wireshark
- Npcap
- Windows OS
- Active Wi-Fi network

## 📚 Topics Covered
- IP Address, MAC Address, DNS
- TCP vs UDP
- Live packet capture
- Protocol-based filtering (DNS, TCP, HTTP)
- TCP three-way handshake
- Plain-text vs encrypted traffic
- DNS query analysis
- Saving packet captures

## 🔍 Key Observations
- DNS queries were visible in plain text and resolved domain names to IP addresses.
- TCP connections followed the standard three-way handshake (SYN, SYN-ACK, ACK).
- HTTPS/TLS traffic was encrypted and unreadable, highlighting secure communication.
- Captured packets were saved in `.pcapng` format for future analysis.

## 📂 Files Included
- `Task_3_Wireshark_Network_Analysis_Detailed_Report.pdf` – Detailed report
- `screenshots/` – Evidence of packet capture and analysis
- `sample_capture.pcapng` – Saved packet capture (optional)
