# Network-Traffic-Analysis
Objective: Capture and analyze network traffic to identify unusual patterns, malware, or signs of an attack.

## Tools Used
- Wireshark
- Windows Command Prompt

## Methodology
1. Installed Wireshark.
2. Captured network traffic through Wi-Fi.
3. Generated web browsing traffic.
4. Applied protocol filters.
5. Analyzed packet behavior.

## Protocols Observed

### DNS
Converts domain names into IP addresses.

### TCP
Provides reliable communication between devices.

### TLS
Encrypts web traffic over internet.

### ICMP
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

## Findings
- Majority of traffic used TCP.
- Web traffic was encrypted using TLS.
- DNS queries were observed during website access.
- ICMP packets appeared during ping testing.
- No malicious traffic was detected.

## Conclusion
Network traffic was successfully captured and analyzed using Wireshark. The project demonstrated packet sniffing, protocol analysis, and basic network monitoring techniques.
