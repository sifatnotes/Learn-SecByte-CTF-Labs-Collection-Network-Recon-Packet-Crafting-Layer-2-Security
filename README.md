# Learn-SecByte-CTF-Labs-Collection-Network-Recon-Packet-Crafting-Layer-2-Security
A curated collection of hands-on cybersecurity CTF labs covering Scapy Packet Crafting, Nmap Network Scanning, ARP Spoofing, DNS Spoofing, DHCP Security, and VLAN Hopping from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on custom packet crafting using Scapy, advanced Nmap network scanning, service banner grabbing, protocol enumeration, and Layer 2/3 protocol security labs—including ARP spoofing, MAC flooding, DHCP starvation, DNS spoofing, and VLAN hopping—designed for cybersecurity students, CTF players, network penetration testers, SOC analysts, and ethical hackers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Understanding fundamental network mechanics requires hands-on experience with low-level packet manipulation, network scanning, protocol enumeration, and Layer 2/3 attack vectors. Hosted on [Learn SecByte](https://learn.secbyte.org/), this advanced network reconnaissance, packet manipulation, and protocol defense collection provides practical, hands-on technical training to analyze, execute, and defend against network-level attacks.

From crafting custom raw TCP/IP frames with Scapy, executing stealthy Nmap scans, and performing service banner grabbing to attacking and securing core network infrastructure protocols (ARP, DNS, DHCP, 802.1Q VLAN tags, and CAM switch tables), these exercises establish core network pentesting and defense capabilities.

---

## Lab Collection & Index

Below is the complete, searchable index of all packet crafting, network scanning, service enumeration, and Layer 2/3 protocol security challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Packet Crafting with Scapy** | Packet Manipulation & Network Reconnaissance | Crafting custom TCP/UDP/IP headers, forging raw ethernet frames, constructing custom handshakes, packet injection | [Access Lab](https://learn.secbyte.org/ctf/packet-crafting-with-scapy) |
| 2 | **Network Scanning with Nmap** | Packet Manipulation & Network Reconnaissance | SYN/ACK/UDP scanning modes, OS fingerprinting, timing templates (`-T0` to `-T5`), firewall/IDS evasion techniques | [Access Lab](https://learn.secbyte.org/ctf/network-scanning-with-nmap-2) |
| 3 | **Network Reconnaissance Techniques** | Packet Manipulation & Network Reconnaissance | Passive/active network discovery, topology mapping, ICMP sweep techniques, host discovery automation | [Access Lab](https://learn.secbyte.org/ctf/network-reconnaissance-techniques) |
| 4 | **Banner Grabbing Techniques** | Service Enumeration & Banner Grabbing | Netcat/Telnet banner retrieval, HTTP response header inspection, SSL/TLS cert parsing, service version identification | [Access Lab](https://learn.secbyte.org/ctf/banner-grabbing-techniques) |
| 5 | **Service Enumeration Mastery Lab** | Service Enumeration & Banner Grabbing | Deep service probing (SMB, SSH, FTP, SNMP, RPC), Nmap Scripting Engine (NSE) execution, protocol state auditing | [Access Lab](https://learn.secbyte.org/ctf/service-enumeration-mastery-lab) |
| 6 | **ARP Spoofing and Defense: From Network Layer Deception to Detection** | Layer 2/3 Protocol Security & Attacks | ARP cache poisoning, Man-in-the-Middle (MitM) traffic interception, Dynamic ARP Inspection (DAI) defense | [Access Lab](https://learn.secbyte.org/ctf/arp-spoofing-and-defense-from-network-layer-deception-to-det) |
| 7 | **MAC Flooding Attacks: From Switch Tables to Defense** | Layer 2/3 Protocol Security & Attacks | CAM table exhaustion attacks, switch fail-open behavior, hub mode analysis, Port Security configuration | [Access Lab](https://learn.secbyte.org/ctf/mac-flooding-attacks-from-switch-tables-to-defense) |
| 8 | **VLAN Hopping Attacks: From Theory to Detection** | Layer 2/3 Protocol Security & Attacks | Double tagging (802.1Q), Dynamic Trunking Protocol (DTP) abuse, native VLAN misconfiguration exploitation | [Access Lab](https://learn.secbyte.org/ctf/vlan-hopping-attacks-from-theory-to-detection) |
| 9 | **DHCP Starvation Attack: From Discovery to Defense** | DHCP & DNS Infrastructure Security | DHCP DISCOVER flooding, IP pool exhaustion, rogue DHCP server rogue deployment, DHCP Snooping defense | [Access Lab](https://learn.secbyte.org/ctf/dhcp-starvation-attack-from-discovery-to-defense) |
| 10 | **DHCP Security: From Discovery to Defense** | DHCP & DNS Infrastructure Security | Securing DHCP infrastructure, binding database validation, option 82 relay agent information, trusted port rules | [Access Lab](https://learn.secbyte.org/ctf/dhcp-security-from-discovery-to-defense) |
| 11 | **DNS Spoofing: From Name Resolution to Network Defense** | DHCP & DNS Infrastructure Security | DNS cache poisoning, rogue response injection, MitM redirection, DNSSEC validation, response rate limiting | [Access Lab](https://learn.secbyte.org/ctf/dns-spoofing-from-name-resolution-to-network-defense) |
| 12 | **DNS Security: From Resolution to Resilience** | DHCP & DNS Infrastructure Security | DNSSEC zone signing, RPZ (Response Policy Zones), DNS over HTTPS/TLS (DoH/DoT) deployment, amplification mitigation | [Access Lab](https://learn.secbyte.org/ctf/dns-security-from-resolution-to-resilience) |

---

## Categories

### 1. Packet Manipulation & Network Reconnaissance
Master custom raw frame injection using Python Scapy, execute advanced Nmap scanning, and perform network-wide topology discovery.
- [Packet Crafting with Scapy](https://learn.secbyte.org/ctf/packet-crafting-with-scapy)
- [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-2)
- [Network Reconnaissance Techniques](https://learn.secbyte.org/ctf/network-reconnaissance-techniques)

### 2. Service Enumeration & Banner Grabbing
Probe open ports, extract application banners, execute custom Nmap Scripting Engine (NSE) scripts, and audit active network services.
- [Banner Grabbing Techniques](https://learn.secbyte.org/ctf/banner-grabbing-techniques)
- [Service Enumeration Mastery Lab](https://learn.secbyte.org/ctf/service-enumeration-mastery-lab)

### 3. Layer 2/3 Protocol Attacks & Network Evasion
Execute ARP cache poisoning, exhaust switch CAM tables via MAC flooding, perform 802.1Q VLAN double-tagging attacks, and enforce switchport defenses.
- [ARP Spoofing and Defense: From Network Layer Deception to Detection](https://learn.secbyte.org/ctf/arp-spoofing-and-defense-from-network-layer-deception-to-det)
- [MAC Flooding Attacks: From Switch Tables to Defense](https://learn.secbyte.org/ctf/mac-flooding-attacks-from-switch-tables-to-defense)
- [VLAN Hopping Attacks: From Theory to Detection](https://learn.secbyte.org/ctf/vlan-hopping-attacks-from-theory-to-detection)

### 4. DHCP & DNS Infrastructure Security
Exhaust DHCP IP address pools, intercept rogue DHCP offers, perform DNS cache poisoning, and configure hardening controls like DHCP Snooping and DNSSEC.
- [DHCP Starvation Attack: From Discovery to Defense](https://learn.secbyte.org/ctf/dhcp-starvation-attack-from-discovery-to-defense)
- [DHCP Security: From Discovery to Defense](https://learn.secbyte.org/ctf/dhcp-security-from-discovery-to-defense)
- [DNS Spoofing: From Name Resolution to Network Defense](https://learn.secbyte.org/ctf/dns-spoofing-from-name-resolution-to-network-defense)
- [DNS Security: From Resolution to Resilience](https://learn.secbyte.org/ctf/dns-security-from-resolution-to-resilience)

---

## Learning Path

Follow this structured progression path to master raw packet manipulation, network scanning, service fingerprinting, and Layer 2/3 protocol defense:

1. **Phase 1: Network Reconnaissance, Nmap Scanning & Packet Crafting** — Learn low-level packet injection with Scapy and master Nmap scanning:
   - [Network Reconnaissance Techniques](https://learn.secbyte.org/ctf/network-reconnaissance-techniques)
   - [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-2)
   - [Packet Crafting with Scapy](https://learn.secbyte.org/ctf/packet-crafting-with-scapy)

2. **Phase 2: Banner Grabbing & Deep Service Enumeration** — Extract application metadata, audit running services, and execute NSE scripts:
   - [Banner Grabbing Techniques](https://learn.secbyte.org/ctf/banner-grabbing-techniques)
   - [Service Enumeration Mastery Lab](https://learn.secbyte.org/ctf/service-enumeration-mastery-lab)

3. **Phase 3: Layer 2 Protocol Attacks & Switch Hardening** — Poison ARP tables, exhaust CAM tables, bypass VLAN tags, and enforce switch defenses:
   - [ARP Spoofing and Defense: From Network Layer Deception to Detection](https://learn.secbyte.org/ctf/arp-spoofing-and-defense-from-network-layer-deception-to-det)
   - [MAC Flooding Attacks: From Switch Tables to Defense](https://learn.secbyte.org/ctf/mac-flooding-attacks-from-switch-tables-to-defense)
   - [VLAN Hopping Attacks: From Theory to Detection](https://learn.secbyte.org/ctf/vlan-hopping-attacks-from-theory-to-detection)

4. **Phase 4: DHCP & DNS Infrastructure Attacks and Defense** — Execute DHCP starvation, spoof DNS records, configure DHCP Snooping, and deploy DNSSEC:
   - [DHCP Starvation Attack: From Discovery to Defense](https://learn.secbyte.org/ctf/dhcp-starvation-attack-from-discovery-to-defense)
   - [DHCP Security: From Discovery to Defense](https://learn.secbyte.org/ctf/dhcp-security-from-discovery-to-defense)
   - [DNS Spoofing: From Name Resolution to Network Defense](https://learn.secbyte.org/ctf/dns-spoofing-from-name-resolution-to-network-defense)
   - [DNS Security: From Resolution to Resilience](https://learn.secbyte.org/ctf/dns-security-from-resolution-to-resilience)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives, protocol parameters, and target specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy security toolsets (Scapy, Nmap, Wireshark, Ettercap, Yersinia, dsniff, Netcat, Bind9, Cisco IOS CLI) inside an isolated workstation.
4. Craft raw network packets, run stealthy port scans, poison ARP/DNS caches, configure Dynamic ARP Inspection and DHCP Snooping, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never execute raw packet crafting scripts, ARP/DNS spoofing attacks, or DHCP starvation tools against unauthorized production networks, public Wi-Fi infrastructure, or third-party cloud systems.
