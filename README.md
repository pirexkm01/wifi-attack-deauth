# WiFi Audit Script

Simple Bash script for wireless auditing and monitor mode management using Aircrack-ng tools.

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

2. Install Aircrack-ng
sudo apt install aircrack-ng -y

Installs Aircrack-ng tools required for monitor mode and packet capture.

3. Install Wireless Tools
sudo apt install wireless-tools -y

Installs utilities like iwconfig.

4. Install Terminal Package (Optional)

Choose your terminal emulator depending on your desktop environment.

GNOME
sudo apt install gnome-terminal -y
XFCE
sudo apt install xfce4-terminal -y
KDE
sudo apt install konsole -y
Clone Project
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
Enter Project Directory
cd YOUR_REPOSITORY
Give Execute Permission
chmod +x script.sh
Run Script
sudo ./script.sh
Features
Detect wireless interfaces
Enable monitor mode
Open scan window automatically
Capture packets from selected target
Save capture files automatically
Multi-terminal support
Output

Captured files are saved in:

~/Desktop/hack1

Generated files may include:

.cap
.csv
.netxml
Supported Systems
Kali Linux
Parrot OS
Ubuntu
Debian
Troubleshooting
Interface Not Found

Check available interfaces:

iwconfig
Monitor Mode Issues

Stop interfering services:

sudo airmon-ng check kill
Permission Denied

Run the script with sudo:

sudo ./script.sh
Legal Disclaimer

This project is intended for:

Educational purposes
Wireless security research
Authorized penetration testing

Do not use this project on networks without permission.

Author


Instagram: @SIIR_PIREX
 
#attack deauth in c
sudo aireplay-ng --deauth 0 -a {bssid} {interface}

0 --->  aut all machine  conecte in the wifi
