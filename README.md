# Network Discovery & Port Scanner

A lightweight Python-based network scanner built to demonstrate practical networking skills through:

- ARP-based host discovery
- TCP connect scanning of common service ports
- Basic banner grabbing
- Optional Shodan enrichment
- JSON, CSV, and human-readable report output

## Overview

This project was created as a networking-focused portfolio piece.  
Rather than emphasizing advanced software engineering, it highlights core networking concepts such as:

- IPv4 subnet validation
- Layer 2 host discovery with ARP
- TCP port and service enumeration
- Basic service identification
- Network inventory reporting

The scanner is intended for use in a home lab or other authorized environment.

## Features

- Validates and normalizes IPv4 subnets in CIDR format
- Uses **ARP scanning** to identify live hosts on the local subnet
- Scans common TCP ports on discovered hosts
- Attempts lightweight banner grabbing on select services
- Optionally pulls host intelligence from **Shodan**
- Exports results in:
  - JSON
  - CSV
  - Human-readable text report
- Supports concurrent scanning with configurable worker threads

## Technologies Used

- Python 3
- `socket`
- `ipaddress`
- `concurrent.futures`
- `scapy` (for ARP discovery)
- `requests` (for optional Shodan lookups)

## Why I Built This

I built this project to demonstrate foundational networking skills in a practical way.

This scanner shows my understanding of:

- how hosts are discovered on a subnet
- how ARP works at Layer 2
- how TCP services are identified through port scanning
- how service inventory can be documented and exported
- how external intelligence sources like Shodan can enrich findings


