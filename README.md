# 🖥 Installing Windows 11 ARM on VirtualBox (macOS Apple Silicon)

## 📌 Overview

This project demonstrates how to install and configure a Windows 11 ARM virtual machine on a macOS system using VirtualBox (Apple Silicon).  

The goal was to create a secure and isolated Windows environment for cybersecurity labs, tool testing, and security research.

---

## 🎯 Objectives

- Install VirtualBox on macOS (Apple Silicon)
- Deploy Windows 11 ARM in a virtual environment
- Configure RAM, storage, and networking
- Prepare a fully functional Windows VM for cybersecurity labs

---

## 🛠 Tools & Technologies Used

- VirtualBox (Apple Silicon Version)
- macOS (M1/M2)
- Windows 11 ARM64 ISO
- NAT Networking

---

## 🧪 Installation & Configuration Process

### 1️⃣ Install VirtualBox

- Download VirtualBox for macOS (Apple Silicon/Host version)
- Open the installer package
- Complete installation
- Remove unnecessary .bin files
- Launch VirtualBox

---

### 2️⃣ Download Windows 11 ARM

- Download Windows 11 ARM64 (English)
- Verify ISO file download completion

---

### 3️⃣ Create the Virtual Machine

- Click **New**
- Name the VM:

```
Windows11ARM64
```

- Type: Microsoft Windows
- Version: Windows 11 (ARM64)

---

### 4️⃣ Configure System Resources

- Allocate RAM (based on host capacity)
- Create virtual hard disk
- Review base configuration

---

### 5️⃣ Advanced Configuration (Expert Mode)

#### General
- Shared Clipboard → **Bidirectional**

#### Display
- Default configuration (no changes)

#### Storage
- Attach Windows 11 ARM ISO file

#### Network
- Adapter 1 → **NAT**
    - Allows internet access
    - Keeps VM isolated
    - Safer for cybersecurity labs

---

### 6️⃣ Install Windows 11

- Start the VM
- Select language and region
- Accept license terms
- Complete Windows installation
- Finish initial setup

---

## ✅ Final Result

- Windows 11 ARM successfully installed
- VM boots correctly
- Internet connectivity confirmed
- Environment ready for cybersecurity lab usage

---

## 🔐 Cybersecurity Relevance

- Safe environment for malware analysis
- Supports penetration testing labs
- Prevents risk to host OS
- Ideal for Red Team / Blue Team practice
- Allows secure tool experimentation

---

## 📚 What I Learned

- Virtualization on Apple Silicon
- ARM vs x64 architecture differences
- Proper VM resource allocation
- Network isolation using NAT
- Secure lab setup best practices

---

## ⚠️ Disclaimer

This project was conducted in a controlled lab environment for educational and cybersecurity training purposes only.
