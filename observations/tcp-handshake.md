# TCP Three-Way Handshake Observation

## Objective
To observe how TCP establishes reliable communication between client and server.

## Observation
The following sequence was captured in Wireshark:

1. SYN
2. SYN-ACK
3. ACK

The client initiated connection establishment and the server acknowledged the request before communication started.

## Key Learning
TCP uses a three-way handshake to establish reliable communication and synchronize connection parameters before data transfer.