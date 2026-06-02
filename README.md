# Network Traffic Analysis using Wireshark

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

## Conclusion

This project provided hands-on exposure to packet analysis, protocol behavior and network security fundamentals relevant to cybersecurity and cyber resilience.
