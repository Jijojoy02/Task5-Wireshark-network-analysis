
# 🌐 Capture and Analyze Network Traffic Using Wireshark

## Overview
Captured live network traffic using Wireshark, applied protocol filters, and identified multiple protocols in the traffic flow. Findings were documented along with a `.pcap` file export.

## Steps Performed
1. Installed Wireshark on system.
2. Selected active network interface and started packet capture.
3. Generated traffic by:
   - Visiting example.com in browser.
   - Pinging google.com.
4. Stopped capture after ~60 seconds.
5. Applied filters: `http`, `dns`, `tcp`.
6. Identified multiple protocols.
7. Exported capture as `network_capture.pcap`.
8. Summarized key findings.

## Identified Protocols
- **DNS** – Domain name resolution queries and responses.
- **HTTP** – Clear-text web requests and responses.
- **ICMP** – Ping requests and replies.

## Exported Files
- `network_capture.pcap` – Full packet capture.
- `protocol_analysis.md` – Detailed analysis of observed protocols.

## Summary
Wireshark provides deep visibility into network communications, allowing identification of protocols, endpoints, and packet-level data for security monitoring and troubleshooting.
