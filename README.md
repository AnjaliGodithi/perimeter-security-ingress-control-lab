# Perimeter Security Orchestration & Ingress Control

## Executive Summary
This project demonstrates enterprise firewall hardening using a default-deny ingress control strategy. Firewall rules were implemented, validated through connectivity testing, and documented with proof-of-work evidence and troubleshooting diagnostics.

---

## 🎯 Objective
To secure a host by configuring firewall policies that restrict inbound traffic, allow only approved services, and validate rule enforcement using repeatable test cases.

---

## 🔐 Security Policy
- Default deny (all inbound blocked by default)
- Outbound allowed
- Only explicit approved ports/services are permitted

---

## 🛠️ Tools Used
- Windows PowerShell
- Windows Defender Firewall
- netsh advfirewall
- Test-NetConnection

---

## Repository Structure
- `proof/` → screenshots (before/after + validation evidence)  
- `diagnostics/` → errors encountered and fixes  

---

## 📄 Documentation
- [Technical Report](REPORT.md)


