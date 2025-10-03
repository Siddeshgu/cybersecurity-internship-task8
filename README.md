# cybersecurity-internship-task8
# Task 8: Working with VPNs  

This repository contains instructions and documentation for **Task 8: Working with VPNs**.  
The task demonstrates how to install, configure, and verify a VPN connection, along with before-and-after testing of IP addresses and browsing behavior.  

---

## 📌 What is a VPN?  
A **Virtual Private Network (VPN)** is a service that creates a secure, encrypted connection between your device and the internet.  

### ✅ Benefits of VPN:
- **Privacy**: Hides your IP address and online activities.  
- **Security**: Encrypts your internet traffic.  
- **Access Control**: Lets you bypass region restrictions.  
- **Safe Public Wi-Fi**: Protects data on insecure networks.  

---

## ⚙️ Steps Performed  

### Step A: Check Operating System  
- Go to `Settings → System → About` OR run `winver` in PowerShell.  

### Step B: Install VPN  
- Download VPN software (e.g., ProtonVPN).  
- Run the installer and complete setup.  
- 📸 *Screenshot: Installation completion page*  

### Step C: Configure VPN  
- Open the VPN client and sign in.  
- Select a VPN server (e.g., Singapore, Germany, US).  
- 📸 *Screenshot: VPN server selection page*  

---

## 🛠️ Actions  

### Action 1 – Check IP Before VPN  
Run the following in **PowerShell (Admin mode):**  
```powershell
(Invoke-WebRequest -Uri "https://api.ipify.org").Content
