# Packet Analysis with Wireshark
This repository contains my analysis of network packets captured using Wireshark. The goal was to inspect different protocols, including DNS, IP, TCP, HTTP, and UDP, and extract relevant information from the packet data.

🔍 Objective

    Capture and analyze network traffic using Wireshark
    Identify and understand the structure of DNS, IP, TCP, HTTP, and UDP packets
    Extract useful details from the captured packets

📌 Captured Protocols
1️⃣ IP (Internet Protocol)

    Source & destination IP addresses
    Packet size & fragmentation details

2️⃣ TCP (Transmission Control Protocol)

    3-way handshake (SYN, SYN-ACK, ACK)
    Sequence & acknowledgment numbers
    Flags like RST, FIN, PSH

3️⃣ UDP (User Datagram Protocol)

    Connectionless data transfer
    Port numbers & payload size

4️⃣ DNS (Domain Name System)

    Query & response analysis
    IP resolution from domain names

5️⃣ HTTP (HyperText Transfer Protocol)

    Request & response headers
    GET and POST requests

🛠 How to Capture Packets

    Open Wireshark
    Select the appropriate network interface
    Start capturing traffic
    Use filters like:
        ip → Capture all IP packets
        tcp → Capture TCP packets
        udp → Capture UDP packets
        dns → Capture DNS queries and responses
        http → Capture HTTP traffic
    Analyze packet details in the Packet Details & Packet Bytes pane

📊 Findings & Insights

    Observed DNS requests resolving domain names to IPs
    Detected TCP handshake process for web requests
    Analyzed HTTP request/response headers for web browsing
    Identified UDP-based traffic patterns
