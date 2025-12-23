# ARP Spoofing (ARP Poisoning)

## 📌 Overview
ARP Spoofing (also known as ARP Poisoning) is a **Man-in-the-Middle (MITM)** attack technique used in local area networks (LAN).  
In this attack, an attacker sends fake ARP replies to associate their MAC address with the IP address of another device (usually the gateway).

---

## 🧠 What is ARP?
**ARP (Address Resolution Protocol)** maps an IP address to a MAC address in a local network.
![Image](https://github.com/user-attachments/assets/249b7d2d-ec76-4df9-9737-21e19097ac83)

Example:
- IP: `192.168.56.102`
- MAC: `8:0:27:1f:b7:23`
- <img width="666" height="525" alt="Image" src="https://github.com/user-attachments/assets/5d69d561-011e-4e4a-8827-7218c1da9c86" />

ARP has **no authentication**, which makes it vulnerable.

---

## ⚔️ How ARP Spoofing Works
1. Attacker scans the local network
2. Attacker sends forged ARP replies
3. Victim believes attacker is the router
4. Traffic passes through attacker
5. Attacker can sniff, modify, or block data
6. <img width="957" height="1017" alt="Image" src="https://github.com/user-attachments/assets/df8bcd27-8bbc-46b4-9baf-399a15d3ce83" />

---

## 🎯 Impact of ARP Spoofing
- Packet sniffing
- Session hijacking
- Credential theft
- DNS spoofing
- MITM attacks
- <img width="957" height="1017" alt="Image" src="https://github.com/user-attachments/assets/6ba4dc97-cb05-4fb3-a947-c26c6619a487" />

---

## 🛡️ Prevention Techniques
- Use **Static ARP entries**
- Enable **Dynamic ARP Inspection (DAI)**
- Use **HTTPS / TLS**
- Monitor ARP tables
- Use IDS/IPS systems
![Image](https://github.com/user-attachments/assets/50782f4e-bd4c-40e9-9e0e-1df39a838a0c)
---

## 🧪 Learning Environment
This concept should be practiced only in:
- Virtual labs
- Test networks
- CTF challenges
- Authorized environments

---

## ⚠️ Disclaimer
This repository is created **strictly for educational and ethical purposes only**.  
Any misuse of this knowledge is the sole responsibility of the user.

---

## 📚 References
- RFC 826 – Address Resolution Protocol
- OWASP Network Attacks
- MITRE ATT&CK Framework
