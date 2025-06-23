# nmap-network-scan
# 🔍 Nmap Network Scan – Local Host

## 🧠 Objective
To scan the local device (`192.168.1.34`) using **Nmap** and identify open ports and services, helping to understand exposure to potential risks.

## 🧰 Tools Used
- Nmap 7.97 (TCP SYN scan)
- Windows 10 Command Prompt

## 📂 Files Included
- `scan_results.txt`: Raw scan output from Nmap
- `scan_results_annotated.txt`: Scan output with descriptions added
- (Optional) `screenshot.png`: Terminal screenshot of the scan (upload if available)

## 🧾 Scan Command Used
```bash
nmap -sS -oN scan_results.txt 192.168.1.34

