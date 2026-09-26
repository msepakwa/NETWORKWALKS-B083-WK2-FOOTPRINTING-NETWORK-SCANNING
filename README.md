# NETWORKWALKS-B083-WK2-FOOTPRINTING-NETWORK-SCANNING
# Networkwalks — Week 2: Footprinting & Network Scanning

## Overview

This repository documents my **Week 2 Networkwalks cybersecurity training**, focused on penetration-testing reconnaissance, footprinting, GHDB exercises, and network scanning.

## Objectives

* Perform reconnaissance and information gathering
* Enumerate DNS and domain information
* Identify web technologies and security controls
* Practice Google Hacking Database (GHDB) techniques
* Discover hosts on an authorized local network
* Document findings and supporting evidence

## Tools

| Tool     | Purpose                       |
| -------- | ----------------------------- |
| WHOIS    | Domain reconnaissance         |
| WhatWeb  | Web technology fingerprinting |
| Nslookup | DNS resolution                |
| cURL     | HTTP header analysis          |
| WAFW00F  | WAF detection                 |
| DNSRecon | DNS enumeration               |
| Nmap     | Network discovery             |
| Zenmap   | Graphical Nmap interface      |

## Assessment Areas

### Footprinting & Reconnaissance

The assessment included:

* WHOIS information
* DNS enumeration
* Web technology fingerprinting
* HTTP header analysis
* WAF detection

### GHDB Exercises

Educational Google dorking exercises covering:

* Webcam-related searches
* Directory-index and mathematics resources

These entries are documented as training exercises and are not presented as confirmed vulnerabilities.

### Network Scanning

Authorized local network:

```text
Network:   10.53.183.0/24
Interface: wlan0
Local IP:  10.53.183.196
```

Latest ARP-based discovery identified:

```text
10.53.183.177
10.53.183.196
```

**Hosts discovered: 2**

Host discovery results may vary depending on network conditions and scanning method.

## Evidence

The repository contains:

* `report/` — final penetration-testing report
* `evidence/` — command outputs
* `screenshots/` — supporting visual evidence
* `notes/` — GHDB exercises and supporting notes

## Scope & Ethics

Testing was performed within an authorized educational environment.

No unauthorized access or credential use was performed.

Techniques documented in this repository should only be used against systems for which explicit authorization has been provided.
