# 🕵️ Ettercap - Man in the Middle Attack (MITM)

This project demonstrates how to perform a **Man-in-the-Middle (MITM) attack** using **Ettercap** on **Ubuntu Mate**. The documentation includes attached screenshots and videos that explain step-by-step how Ettercap can be utilized for network traffic interception and monitoring.

---

## ⚡ Overview

* **Tool Used**: Ettercap
* **Platform**: Ubuntu Mate
* **Attack Type**: Man-in-the-Middle (MITM)

Ettercap allows you to:

* Intercept and manipulate traffic on a **Local Area Network (LAN)**.
* Divert or block access to specific websites for target users.
* Monitor network traffic in real-time.

⚠️ **Note**: Ettercap is only useful on **local networks (LAN)**. It will not work effectively on wide area networks (WAN).

---

## 🎯 Features

* Perform MITM attacks easily on a LAN.
* Divert network traffic from target users.
* Block or restrict access to unwanted websites.
* Real-time network traffic monitoring.

---

## 🛠️ Requirements

* Ubuntu Mate (or any Linux distribution with support for Ettercap).
* Ettercap installed.
* Local Area Network (LAN) setup.

---

## 🚀 Usage

1. Install Ettercap on Ubuntu Mate:

   ```bash
   sudo apt update && sudo apt install ettercap-graphical -y
   ```

2. Launch Ettercap in graphical mode:

   ```bash
   sudo ettercap -G
   ```

3. Select network interface.

4. Scan and select target hosts.

5. Choose MITM attack method (e.g., ARP poisoning).

6. Start the attack and monitor/divert/block traffic as needed.

---

## ⚠️ Disclaimer

This project is created **strictly for educational purposes**.
Unauthorized use of MITM attacks on networks without permission is **illegal**. Always practice ethical hacking on your own test networks or with explicit authorization.

---

## 👤 Author

**Abdul Hannan**
GitHub: [@abdul-hannan-SE](https://github.com/abdul-hannan-SE)
