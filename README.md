# Task-3

# Networking Basics for Cyber Security

## Task Overview
- Learned basic networking concepts (IP, MAC, DNS, TCP/UDP).
- Used Wireshark to capture and analyze live network traffic.
- Goal: Understand how data moves on networks and spot security differences.

## What I Did
- Installed Wireshark (free tool).
- Captured live traffic while browsing websites.
- Filtered packets by protocol: HTTP, DNS, TCP.
- Observed TCP three-way handshake.
- Compared plain-text (HTTP) vs encrypted (HTTPS) traffic.
- Captured and analyzed DNS queries.
- Saved the capture file (.pcapng).
- Wrote simple observations.

## Key Observations
- **Filtering**: Used `http`, `dns`, `tcp` filters to focus on specific traffic.
- **TCP Handshake**: Saw SYN → SYN-ACK → ACK sequence (3 packets) when connecting to websites.
- **Plain-text vs Encrypted**:
  - HTTP: readable GET requests, headers, content (insecure).
  - HTTPS: only TLS handshake visible, then encrypted data (secure).
- **DNS Queries**: Captured UDP port 53 packets showing domain → IP resolution (plain-text by default).
- HTTPS is more secure than HTTP because it encrypts data with TLS.

## Tools Used
- Primary: Wireshark
- No paid tools were used

## Learnings
- Understood how TCP ensures reliable connections.
- Saw why encryption (HTTPS) protects data from sniffing.
- Learned how DNS works and why it is usually unencrypted.
- Got hands-on experience with packet analysis.
