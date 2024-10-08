# Computer Networks Course Project

**Instructor**: Prof. Mizanian  
**Student**: Hossein Goli (Student ID: 99102123)  
**Semester**: Summer 2024

## Contents
1. TUN/TAP Functionality
2. Handshake Mechanism between Client and Server
3. Packet Processing Overview
4. EDNS Functionality
5. Results

## Project Overview

This project demonstrates the implementation of a TUN/TAP virtual interface for manipulating outgoing TCP packets. The implementation includes setting up a client-server communication using a handshake mechanism, handling packet processing, and EDNS packet encapsulation. Key features include:

- Creation of TUN interface for routing and manipulating network traffic.
- Client-server handshake mechanism for establishing secure communication.
- Detailed packet processing pipeline with TCP and EDNS handling.

## Key Technologies
- Python
- Socket Programming
- TUN/TAP Device Handling
- EDNS (Extension mechanisms for DNS)

## Running the Project

To run the server and client, follow these steps:

1. Set the IP and port in the respective scripts.
2. Run the following commands:

```bash
./run_server.sh
./run_client.sh
