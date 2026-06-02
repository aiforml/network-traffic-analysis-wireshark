# Network Traffic Analysis using Wireshark

## Project Preview

![Wireshark Traffic Analysis](screenshots/http_traffic.png)

## Overview

This project explores fundamental network communication and security concepts through practical traffic analysis using Wireshark.

The objective was to observe how network protocols operate, compare unencrypted and encrypted communication, and understand the security implications of network visibility.

## Objectives

* Observe TCP connection establishment
* Analyze HTTP traffic
* Compare HTTP and HTTPS communication
* Understand TLS-based encryption
* Explore security implications of packet visibility

## Tools Used

* Wireshark
* Windows
* Web Browser
* Basic Networking Concepts

## Experiments Performed

### 1. TCP Three-Way Handshake

Observed SYN, SYN-ACK and ACK packets during connection establishment.

### 2. HTTP Traffic Analysis

Captured unencrypted HTTP traffic and observed readable request data.

### 3. HTTPS / TLS Analysis

Observed TLS handshake and encrypted communication over HTTPS.

## Key Security Learnings

* HTTP traffic is readable and vulnerable to interception.
* HTTPS encrypts communication and protects confidentiality.
* Packet analysis is useful for monitoring and incident investigation.
* Metadata visibility still exists even with encrypted communication.

## Repository Structure

* `observations/` → Technical observations and notes
* `screenshots/` → Wireshark screenshots
* `sample_capture/` → Sample packet capture file

## Learning Outcomes

Through this project I gained practical exposure to:

- TCP connection establishment
- Packet-level traffic observation
- HTTP vs HTTPS communication
- TLS-based encryption concepts
- Network visibility and security implications
- Basic traffic analysis using Wireshark

## Conclusion

This project provided practical exposure to packet analysis and network communication behavior using Wireshark. Through hands-on observation of TCP, HTTP and HTTPS traffic, it strengthened understanding of secure communication, protocol behavior and the role of traffic visibility in cybersecurity and cyber resilience.

