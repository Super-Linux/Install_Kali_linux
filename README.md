
# Install Kali Linux in Termux

A working and legitimate Kali Linux installation script for Termux on Android.

## Prerequisites

- Termux application installed
- Android device with sufficient storage (~3-5GB recommended)
- Internet connection

## Installation

Follow these steps to install Kali Linux:

```bash
pkg update
pkg upgrade
pkg install wget
git clone https://github.com/Super-Linux/Install_Kali_linux.git
cd Install_Kali_linux
chmod +x install_kali.sh
./install_kali.sh
```

## What This Does

The `install_kali.sh` script automates the installation of Kali Linux tools and utilities within your Termux environment.

## Notes

- This installation may take some time depending on your connection speed
- Ensure you have adequate storage space before running the script
- For issues or feature requests, please open an issue on the repository

