# ExitScore

ExitScore is a personal reputation checker for public VPN exit nodes. It helps assess whether your current IP address is clean, stealthy, or burned — before engaging in sensitive ops like phishing takedowns or OSINT sweeps.

## 💡 What It Does

### ExitScore checks your current public IP address and scores it from 1–10 based on:

- Abuse reports (via AbuseIPDB)
- Blacklist presence (via VirusTotal)
- ASN, ISP, and geolocation data (via IPinfo)
- Red flags like datacenter ranges, known proxy/VPN blocks, or high abuse confidence scores

### It outputs:

- A human-readable score in the terminal
- A full JSON/text summary file for logs
- Optional integration with VoxBridge for AI analysis

### 🚪 Use Case

Perfect for:

- Avoiding compromised or overused VPN nodes
- OSINT profiles
- Phishing infrastructure checks

## 🚀 Quick Start

### Clone the repo

### Create a .env file with the following:

```
ABUSEIPDB_KEY=your_api_key
VT_API_KEY=your_api_key
IPINFO_TOKEN=your_api_key
```

### Run the script:

```
./exitscore.sh
```

### Or, for Python:

```
python exitscore.py
```

### Get a clean rating or reconsider your VPN.

## 📦 Roadmap

## ⚠️ Disclaimer

This tool is for educational and ethical research use only. Use responsibly.

## 🙏 Thank You

Thanks for checking out this project. Whether you're here to learn, contribute, or adapt it for your own ops — you’re part of the signal. Respect.

### ☕ Support

If you found this useful, consider supporting the project: https://ko-fi.com/mikesploit

mikesploit | cybersecurity for the curiousno gatekeeping. no ego. just signal.
