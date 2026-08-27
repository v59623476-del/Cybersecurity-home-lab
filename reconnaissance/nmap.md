# Network Reconnaissance with Nmap

## Overview

Nmap was used from the Kali Linux attacker machine to perform network reconnaissance against systems within the controlled cybersecurity lab environment.

## Objectives

- Identify active hosts
- Identify open ports
- Identify running services
- Gather information about the target systems
- Establish a baseline for further security testing

## Tool Used

- Nmap
- Kali Linux

## Methodology

The reconnaissance process involved identifying the target IP address and scanning the authorized lab network.

Example commands used during testing:

```bash
nmap <target-ip>

## Results

### Scan Result

Target IP: 10.0.2.15

The target host was reachable and responded to network probes.

Nmap reported that all 1000 scanned TCP ports were closed and no services were identified during the scan.

## Findings

- Target host was online.
- No open TCP ports were discovered.
- No services were identified through version detection.

## Recommendations

Further enumeration should be performed when additional services become available on the target system.

## Evidence

Screenshots of the Nmap scan results will be added here as supporting evidence.
