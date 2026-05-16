# WiFi Audit Script

Simple Bash script for wireless auditing and monitor mode management using Aircrack-ng  and attack deauth tools.

---

## Features

- Detect wireless interfaces
- Enable monitor mode automatically
- Open scan window with `airodump-ng`
- Capture packets from selected target
- Save capture files automatically
- Multi-terminal support

---

## Requirements

- Linux system
- Wireless adapter supporting monitor mode
- Root privileges

---

# Installation

## 1. Update System Packages

```bash
sudo apt update && sudo apt upgrade -y
```

Updates system repositories and installed packages.

---

## 2. Install Aircrack-ng

```bash
sudo apt install aircrack-ng -y
```

Installs Aircrack-ng tools required for monitor mode and packet capture.

---

## 3. Install Wireless Tools

```bash
sudo apt install wireless-tools -y
```

Installs utilities like `iwconfig`.

---

## 4. Install Terminal Package (Optional)

Choose your terminal emulator depending on your desktop environment.

### GNOME

```bash
sudo apt install gnome-terminal -y
```

### XFCE

```bash
sudo apt install xfce4-terminal -y
```

### KDE

```bash
sudo apt install konsole -y
```

---

# Clone Project

```bash
git clone https://github.com/pirexkm01/wifi-attack-deauth.git
```

---


```

---

# Give Execute Permission

```bash
chmod +x script.sh
```

---

# Run Script

```bash
sudo ./script.sh
```

---

# Usage

1. Run the script
2. Select your wireless interface
3. Enable monitor mode
4. Choose target network
5. Start capture process

---

# Output

Captured files are saved in:

```bash
~/Desktop/hack1
```

Generated files may include:

```text
.cap
.csv
.netxml
```

---

# Supported Systems

- Kali Linux
- Parrot OS
- Ubuntu
- Debian

---

# Troubleshooting

## Interface Not Found

Check available interfaces:

```bash
iwconfig
```

---

## Monitor Mode Issues

Stop interfering services:

```bash
sudo airmon-ng check kill
```

---

## Permission Denied

Run the script with sudo:

```bash
sudo ./script.sh
```

---

# Recommended Adapters

- Alfa AWUS036NHA
- Alfa AWUS036ACH
- TP-Link TL-WN722N v1

---

# Legal Disclaimer

This project is intended for:

- Educational purposes
- Wireless security research
- Authorized penetration testing

Do not use this project on networks without permission.

The author is not responsible for misuse.

---

# Author

Instagram: @SIIR_PIREX

---

# #attack deauth in c


sudo aireplay-ng --deauth 0 -a {bssid} {interface}

 L0 --->  aut all machine  conecte in the wifi
