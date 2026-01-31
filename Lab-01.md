# Lab 01: Enterprise Infrastructure Audit
**Date:** January 2026  
**Status:** In Progress  

## 🎯 Objective
To analyze the 2021 Facebook outage from a systems design perspective and identify the specific failure points in their BGP (Border Gateway Protocol) configuration.

## 🛠️ Tools Used
* Wireshark v4.0.03 (Traffic Analysis)
* Draw.io (Network Topology Mapping)
* Linux Terminal

## 🔍 Key Findings
1. **Root Cause:** A routine maintenance command unintentionally disconnected Facebook's data centers from the wider internet.
2. **Cascading Failure:** Because the network was down, internal tools (like badge readers) also failed, delaying physical access to the servers.

## 💡 Lessons Learned
This lab highlighted the danger of **Single Points of Failure**. In the future, I would recommend out-of-band management for critical infrastructure to ensure access during a primary network collapse.

## 📸 Proof of Work
![Network Diagram Placeholder]<img width="391" height="183" alt="Network 2026-01-30 at 11 19 45 PM" src="https://github.com/user-attachments/assets/a373a77a-7069-405b-99e5-c5b9de489cda" />
