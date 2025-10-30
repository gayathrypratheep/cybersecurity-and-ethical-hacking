This repository contains the full deliverables for my ApexPlanet cybersecurity internship task series. The lab is an isolated VirtualBox network that includes:

Kali Linux — attacker/analysis VM

Metasploitable2 — intentionally vulnerable target VM

Tools used: Nmap, Wireshark, OpenVAS / GVM (or Nessus Essentials), Netcat, BurpSuite, etc.

Goals:

Build a reproducible local pentest lab (VirtualBox host-only network).

Run network discovery and vulnerability scans (Nmap TCP/UDP, -sV, -O).

Install and run a vulnerability manager (GVM / Nessus), scan target VM.

Produce evidence: screenshots, scan outputs, and a 5-minute walkthrough video.

Produce structured lab & vulnerability reports suitable for internship submission.

Rules & Safety

Only scan your own VMs and networks. Do not scan external/public networks without permission.

Take snapshots before running intrusive or exploit-style scans.

Use -T3/-T4 timing in isolated lab only; avoid aggressive scans on shared networks.
