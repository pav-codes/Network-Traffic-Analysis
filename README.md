# Network-Traffic-Analysis
Objective: Capture and analyze network traffic to identify unusual patterns, malware, or signs of an attack.

## Tools Used
- Wireshark
- Npcap
- Windows Command Prompt

## Methodology
1. Installed Wireshark.
2. Captured network traffic which was coming through Wi-Fi connection.
3. Opened some websites to create web traffic.
4. Applied protocol filters.
5. Analyzed how the packets of data were behaving.

## Protocols Observed

### DNS (Domain Name System)
Converts domain names into IP addresses.

### TCP (Transmission Control Protocol)
Provides reliable communication between devices.

### TLS (Transport Layer Security))
Encrypts web traffic over internet.

### ICMP (Internet Control Message Protocol)
Used for network diagnostics and ping operations.

## Screenshots

### Packet Capture
![Capture](screenshots/packet_capture.png)

### DNS Traffic
![DNS](screenshots/dns.png)

### TCP Traffic
![TCP](screenshots/tcp.png)

### TLS Traffic
![TLS](screenshots/tls.png)

### ICMP Traffic
![ICMP](screenshots/icmp.png)

## Observation
- No signs of network attacks detetcted.
- No malicious traffic was detected.

## Conclusion
Network traffic was successfully captured and analyzed with Wireshark. 
The project showed packet sniffing, protocol analysis, and basic network monitoring techniques.
