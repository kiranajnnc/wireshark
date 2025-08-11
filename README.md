
# Cyber Security Internship - Wireshark Network Traffic Analysis

This project provides guides and examples for capturing and analyzing network traffic using Wireshark, as part of a cybersecurity internship task.

## Objectives

- Capture live network packets.
- Identify protocols like HTTP, DNS, TCP, and UDP.
- Analyze captured packets and generate a report.

## Installation

1. Download and install [Wireshark](https://www.wireshark.org/).
2. Follow the usage steps in this repository.

## Usage

- Open Wireshark and select your network interface.
- Start and stop capture.
- Apply filters (e.g., `http`, `tcp`, `dns`).
- Analyze packet details.

answer for interview questions
### Wireshark Interview Questions – Sample Answers

1. *What is Wireshark?*  
Wireshark is a free, open-source network protocol analyzer that allows users to capture, inspect, and analyze data packets traveling through a computer network.

2. *What types of packets are captured in Wireshark?*  
Wireshark can capture a variety of network packets including:
   - Ethernet frames
   - Internet Protocol (IP) packets (IPv4/IPv6)
   - TCP and UDP packets (transport protocols)
   - Application protocols such as HTTP, DNS, FTP, SMTP, ARP, ICMP, etc.

3. *Difference between TCP and UDP:*  
- *TCP (Transmission Control Protocol):*
   - Connection-oriented.
   - Reliable (guarantees delivery).
   - Error-checked and sequenced.
   - Slower due to overhead.
- *UDP (User Datagram Protocol):*
   - Connectionless.
   - Unreliable (no delivery guarantee).
   - No sequencing or error-checking (except basic checksum).
   - Faster, with less overhead.

4. *How to analyze HTTP and DNS traffic in Wireshark?*
   - Use display filters like http or dns in the filter bar to isolate relevant packets.
   - Select individual packets to analyze request and response details (e.g., view HTTP methods, URLs, or DNS queries and responses).
   - Follow TCP/UDP streams for a complete protocol flow.

5. *What are Wireshark filters?*
   - Filters in Wireshark let you display only the packets you care about.
   - Example filters: ip.addr == 192.168.1.1, tcp.port==80, http, dns.
   - Filter syntax allows detailed packet analysis and troubleshooting.

6. *Can Wireshark detect complete attacks?*
   - Wireshark can help identify suspicious network behavior or anomalies (such as port scans, malware communication patterns, or protocol misuse).
   - However, it does not automatically detect or flag “attacks”; you must interpret the data to spot evidence of incidents. Wireshark is a powerful tool for initial investigation and forensic analysis, but it works best as part of a broader security toolkit.

