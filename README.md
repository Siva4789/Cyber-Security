Kali Linux Installation Guide

This section provides step-by-step instructions to install Kali Linux, a Debian-based Linux distribution widely used for penetration testing, ethical hacking, and cybersecurity research.

System Requirements

RAM: Minimum 2 GB (4 GB or more recommended)

Storage: At least 20 GB of free disk space

CPU: Dual-core or higher

USB/DVD drive or Virtualization software (like VirtualBox or VMware)


Installation Methods

You can install Kali Linux in one of three common ways:

1. As a primary OS (bare metal install)


2. Inside a Virtual Machine (VM) – Recommended for beginners


3. Via USB as a live OS




---

Method 1: Install Kali Linux in VirtualBox (Recommended for Beginners)

Step 1: Download Kali Linux ISO

Official website: https://www.kali.org/get-kali/


Choose the Installer ISO or VirtualBox prebuilt image.

Step 2: Install VirtualBox

Download and install VirtualBox from https://www.virtualbox.org.

Step 3: Create a New Virtual Machine

Open VirtualBox → Click New

Name: Kali Linux

Type: Linux

Version: Debian (64-bit)

Memory: Allocate at least 2048 MB

Hard Disk: Create a virtual hard disk now → VDI → Dynamically allocated → At least 20 GB


Step 4: Mount Kali ISO and Start

Go to Settings > Storage > Empty

Click Disk icon → Choose the Kali ISO file

Start the VM and proceed with the graphical install



---

Method 2: Install Kali Linux on Bare Metal (Dual Boot)

WARNING: This can erase your data if not done carefully.

1. Backup your data


2. Download the Kali Linux ISO and create a bootable USB using:

Rufus (Windows)

dd (Linux/Mac)



3. Boot from the USB


4. Choose "Graphical Install"


5. Partition the drive (choose dual boot or full Kali install)


6. Finish the installation and reboot




---

Default Credentials

Username: kali

Password: kali


Post-Installation Tips

Run sudo apt update && sudo apt upgrade to update packages

Install additional tools using sudo apt install <tool-name> or kali-linux-top10



---

Resources

Kali Linux Docs

Offensive Security
