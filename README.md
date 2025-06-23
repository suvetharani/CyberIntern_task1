# 🔍 Local Network Port Scanning with Nmap

This project demonstrates how to scan a local network for open ports using **Nmap** on a Windows machine. The goal is to discover active hosts, identify running services, and evaluate basic network security risks.

---

## 📌 Features

- Scan entire local subnet using Nmap
- Identify open TCP ports on active devices
- Analyze services and assess potential risks
- Save scan results in `.txt` and `.html` formats
- Optional: Inspect packet data using Wireshark

---

## 🛠 Tools Used

- [Nmap](https://nmap.org/download.html)
- [Zenmap (GUI for Nmap)](https://nmap.org/zenmap/)
- [Wireshark](https://www.wireshark.org/) *(optional)*
- Windows Command Prompt

---

## 🧪 Scan Command

```bash
nmap -sS 192.168.208.0/24 > scan_results.txt
```

📁 Output Files
  scan_results.txt – Raw scan output
  nmap_report.html – Formatted HTML report from Zenmap

👩‍💻 Author
Suvetharani – B.Tech IT Student
Passionate about network security and full-stack development.
