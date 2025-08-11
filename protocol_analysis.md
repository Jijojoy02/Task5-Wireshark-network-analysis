
# 📡 Protocol Analysis – Task 5 Wireshark Capture

## DNS (Domain Name System)
- **Purpose:** Resolves human-readable hostnames (e.g., google.com) into IP addresses.
- **Packets Observed:** Multiple A record queries and responses.
- **Security Note:** DNS traffic is usually unencrypted; attackers can monitor it.

## HTTP (HyperText Transfer Protocol)
- **Purpose:** Web communication protocol for fetching web pages.
- **Packets Observed:** HTTP GET request to example.com with HTTP/1.1 200 OK response.
- **Security Note:** HTTP sends data in plaintext, making it vulnerable to sniffing.

## ICMP (Internet Control Message Protocol)
- **Purpose:** Diagnostic protocol used for connectivity checks (ping).
- **Packets Observed:** Echo request and echo reply between local host and google.com.
- **Security Note:** ICMP can be exploited for reconnaissance (e.g., ping sweeps).

## Conclusion
The capture revealed normal browsing and ping activity. DNS, HTTP, and ICMP are common in everyday network usage, but should be monitored for anomalies in a security context.
