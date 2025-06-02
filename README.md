# 📡 Network Packet Capture & Protocol Identification - README

## 🎯 Objective
Capture live network traffic and identify at least three basic network protocols using Wireshark. Analyze packet-level data and summarize key findings.

---

## 🛠️ Tools Used
- **Wireshark** (Free and open-source network protocol analyzer)
- **Browser** / `ping` / for traffic generation

---

## 📋 Steps Performed

1. **Installed Wireshark** and launched it.
2. **Started live capture** on the active network interface.
3. Generated traffic by:
   - Visiting `http://github.com` (HTTPS/TLS)
   - Running `ping google.com` (ICMP)
4. **Captured traffic** for about 1 minute.
5. **Filtered packets** using protocol filters (`http`, `dns`, `icmp`, `tls`, etc.).
6. **Identified protocols**:
   - DNS
   - ICMP
   - HTTP
   - TLS
7. **Saved capture** as `.pcap` file.
8. **Prepared report** with:
   - Protocol-wise summary
   - Packet details
   - Screenshots

---

## 🔎 Protocols Identified

| Protocol | Description                 |
|----------|-----------------------------|
| DNS      | Domain name resolution      |
| ICMP     | Ping (echo request/reply)   |
| HTTP     | Unencrypted web browsing    |
| TLS      | Encrypted HTTPS traffic     |

---

