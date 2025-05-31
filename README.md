# 🔐 Firewall Configuration on Windows & Linux

Welcome to the **Firewall Configuration Project** where I demonstrate how to use firewall tools in **Linux (UFW)** and **Windows Defender Firewall** to control network traffic with basic rules such as blocking or allowing specific ports.

---

## 🎯 Objective

- Configure a firewall on both Linux and Windows
- Block and allow specific ports (e.g., block Telnet port 23, allow SSH port 22)
- Test the applied firewall rules
- Understand how a firewall filters traffic

---

![img alt](https://github.com/santhosheyzz/Firewall-Configuration-Windows-Linux/blob/ff5c8eb27a2e46551fc7be2cb0ca8b1f3d60670a/Task%204%20question.png)

---

## 🛠 Tools Used

| Platform | Tool                         |
|----------|------------------------------|
| Linux    | UFW (Uncomplicated Firewall) |
| Windows  | Windows Defender Firewall    |
| Both     | Telnet Client (for testing)  |

---


![img alt](https://github.com/santhosheyzz/Firewall-Configuration-Windows-Linux/blob/ff5c8eb27a2e46551fc7be2cb0ca8b1f3d60670a/linux/Firewall%20Activate.png)
![img alt](https://github.com/santhosheyzz/Firewall-Configuration-Windows-Linux/blob/ff5c8eb27a2e46551fc7be2cb0ca8b1f3d60670a/linux/Rules%20Upgrade.png)


---
## 🐧 Linux (UFW) Configuration

### 🔸 Commands Used

```bash
# Enable UFW
sudo ufw enable

# View current rules and status
sudo ufw status verbose

# Block port 23 (Telnet)
sudo ufw deny 23

# Test connection
telnet localhost 23

# Allow port 22 (SSH)
sudo ufw allow 22

# Delete the deny rule for port 23
sudo ufw delete deny 23
```
---
## Windows (FIREWALL) Configuration

![img alt](https://github.com/santhosheyzz/Firewall-Configuration-Windows-Linux/blob/ff5c8eb27a2e46551fc7be2cb0ca8b1f3d60670a/Windows/Windows%20Block%20the%20port.png)

![img alt](https://github.com/santhosheyzz/Firewall-Configuration-Windows-Linux/blob/ff5c8eb27a2e46551fc7be2cb0ca8b1f3d60670a/Windows/Windows%20Firewall.png)

---
##🗒️ Additional Notes
  -firewall_commands.txt contains all Linux commands used.
  -All screenshots are labeled clearly and sorted into folders.
  -This project helps develop basic firewall management skills and network security understanding.
---
##👨‍💻 Author
Santhoshkumar
Cybersecurity Enthusiast | Developer | Tech Explorer

---
