# Network Reconnaissance Detection

## Objective
Simulate network reconnaissance activity from an attacker machine.

## Attack Performed

Source: Kali Linux VM

Target: Windows 10 VM

Command:

nmap 192.168.87.131

## Results

Host was reachable.

All 1000 default TCP ports were filtered.

Windows Firewall prevented service enumeration.

## MITRE ATT&CK

T1046 - Network Service Discovery

## Findings

The target system responded to ICMP/network probes but did not expose discoverable TCP services. This demonstrates the effectiveness of host-based firewall controls against basic reconnaissance.