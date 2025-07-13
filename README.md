# task2-nids-suricata
Setup and configuration of a Network Intrusion Detection System using Suricata on Kali Linux

# Task 2: Network Intrusion Detection System with Suricata

This project demonstrates the installation, configuration, and testing of a NIDS using Suricata on Kali Linux.

## Files Included
- `suricata.yaml`: Main configuration file
- `local.rules`: Custom detection rule for ICMP packets
- `fast.log`: Suricata alert log
- `screenshots/`: Visual proof of configuration and alerts

## How to Run
```bash
sudo suricata -c /etc/suricata/suricata.yaml -i eth0
