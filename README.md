# VPN-Setup-and-Evaluation-Report
Understood the role of VPNs in protecting privacy and secure communication
# VPN Setup and Evaluation Report

## Internship Task Overview
This report documents the process of selecting, installing, testing, and analyzing a free VPN service.  
It also includes research on VPN encryption, privacy features, and an evaluation of VPN benefits and limitations.

---

## 1. VPN Service Selection

**Chosen VPN:** ProtonVPN (Free Plan)  
**Website:** [https://protonvpn.com](https://protonvpn.com)

**Reason for Choice:**
- Reputable company known for strong privacy protection.
- Based in Switzerland (strict privacy laws).
- Offers a reliable free plan without data limits.
- No ads or tracking.
- Open-source applications for transparency.

---

## 2. Installation Steps

1. Signed up for a free ProtonVPN account on the official website.
2. Downloaded the ProtonVPN client for Windows/macOS/Linux.
3. Installed the client following on-screen instructions.
4. Logged in using the newly created credentials.

---

## 3. Connecting to a VPN Server

- Opened the ProtonVPN application.
- Selected the **"Quick Connect"** option (auto-connects to the nearest available server).
- Alternatively, users can manually select from free servers in **Netherlands, Japan, or the United States**.

**Server Chosen:** Netherlands (closest free server).

---

## 4. Verifying IP Address Change

- Before connecting: Checked IP using [https://whatismyipaddress.com](https://whatismyipaddress.com)  
  → Original IP Location: India  
- After connecting to VPN:  
  → New IP Location: Netherlands  
✅ **IP address successfully changed.**

---

## 5. Confirming Encrypted Traffic

- Browsed multiple websites including `https://example.com` and `https://github.com`.  
- Confirmed that HTTPS connections remained stable and data was encrypted through ProtonVPN.  
- Used online tools to verify that DNS requests were routed via the VPN.

✅ **Traffic encryption verified.**

---

## 6. Performance Comparison

| Test Type | Without VPN | With VPN (Netherlands) |
|------------|--------------|------------------------|
| Download Speed | ~50 Mbps | ~25 Mbps |
| Upload Speed | ~20 Mbps | ~10 Mbps |
| Ping (Latency) | ~30 ms | ~120 ms |

**Observation:**  
- Browsing and streaming remained smooth but slower.  
- Latency increased due to encrypted tunneling and server distance.

---

## 7. VPN Encryption and Privacy Features

**ProtonVPN Technical Details:**
- **Encryption Protocols:** OpenVPN, IKEv2/IPSec, and WireGuard.
- **Encryption Strength:** AES-256 (military-grade encryption).
- **DNS Leak Protection:** Built-in DNS and IPv6 leak prevention.
- **No-Logs Policy:** Does not record browsing activity or connection logs.
- **Kill Switch:** Automatically disables internet if VPN disconnects, preventing data leaks.
- **Secure Core:** Routes traffic through multiple servers for extra protection (paid feature).

---

## 8. Summary — VPN Benefits and Limitations

### ✅ Benefits
- **Enhanced Privacy:** Hides IP address and location.
- **Data Encryption:** Protects against hackers and surveillance.
- **Bypasses Restrictions:** Access region-locked content.
- **Public Wi-Fi Protection:** Prevents data theft on open networks.
- **No-logs Policy:** Maintains user anonymity (for reputable VPNs).

### ⚠️ Limitations
- **Reduced Speed:** Encryption and server distance lower performance.
- **Free Plan Restrictions:** Limited server access and slower speeds.
- **Not Full Anonymity:** VPN providers can still see metadata (depending on policy).
- **Website Blocks:** Some services (e.g., Netflix, banking sites) may block VPN traffic.

---

## 9. Conclusion

ProtonVPN proved to be a **secure and reliable free VPN solution** for basic browsing and privacy needs.  
While speed is reduced due to encryption overhead, it effectively hides the user's IP and encrypts online activity.  
For enhanced performance and global access, upgrading to a paid plan or using servers closer to the user is recommended.

---

## 🧠 References

- [ProtonVPN Official Website](https://protonvpn.com)
- [WhatIsMyIPAddress.com](https://whatismyipaddress.com)
- [Mozilla VPN Guide](https://www.mozilla.org/en-US/products/vpn/)
- [EFF: Why You Need a VPN](https://www.eff.org/deeplinks/2020/06/why-you-should-use-vpn)

---

**Author:** DORAPALLY KARTHIK  
**Internship Organization:** ELEVATE LABS
**Date:**  31 October 2025

