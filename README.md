# 🕵️ Passive Recon Script

A Bash script for performing passive reconnaissance on a target. It uses publicly available information and OSINT techniques to gather data without directly interacting with the target system.

## 🚀 Features

- DNS lookup
- WHOIS lookup
- IP & ASN info
- Subdomain enumeration
- Passive port and service lookup
- Integration with OSINT tools/APIs (e.g., crt.sh, Shodan, etc.)

## 📦 Requirements

- Bash
- curl
- whois
- dig / host
- jq (if using APIs)

Install required tools on Debian-based systems:

```bash
sudo apt update
sudo apt install curl whois dnsutils jq
