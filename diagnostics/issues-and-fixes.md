# Diagnostics

## Issue: Linux commands not recognized
Commands like `ufw`, `ip`, and `uname` were not available because the environment is Windows (PowerShell/CMD), not Linux.

## Resolution
Used Windows Defender Firewall via `netsh advfirewall` commands to implement ingress control rules.

## Notes
Firewall changes were validated by:
- Confirming firewall profiles enabled
- Creating block and allow inbound rules
- Testing connectivity using Test-NetConnection

