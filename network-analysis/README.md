# Network Traffic Analysis – Wireshark Investigation

## Scenario
Traffic capture performed in a controlled lab environment to identify application behavior over encrypted connections.

## Objective
Understand how applications can be identified even when traffic is encrypted (HTTPS).

## Tools Used
- Wireshark
- Kali Linux
- DNS analysis

## Investigation Steps
- Captured network traffic during browsing session
- Applied DNS filters
- Correlated domain queries with applications
- Analyzed encrypted sessions and traffic patterns

## Findings
Even with HTTPS encryption, DNS queries reveal which services are being accessed (YouTube, Google, etc).
Traffic patterns and endpoints allow identification of applications without decrypting content.

## Security Insight
Encrypted traffic protects content but not metadata.
Attackers and defenders can still identify usage patterns.

## Mitigation
- DNS filtering
- Encrypted DNS (DoH / DoT)
- Network monitoring
- Zero Trust segmentation
