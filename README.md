# IoT & Cyber-Physical Systems Security – Lab Assignment No. 05  
### Seiyun University – Department of Information Security  
### Special Topics in Information Security – 2025  

---

## 📌 Student Information
- **Name:** Omar Abid Baqtian  
- **Enrollment Number:** 22202041008  
- **Email:** (Add your email here)  

---

# 📘 Overview
This repository contains the implementation of **Lab Assignment No. 05: IoT and Cyber-Physical Systems Security**.  
The work includes three practical simulations:

- IoT data encryption using AES  
- IoT device lifecycle modeling  
- Secure boot verification using firmware hashing  

All parts are implemented in **one unified Google Colab notebook** as required.

---

# 🧩 Part I – IoT Device Data Encryption (AES Simulation)
This section simulates a small IoT device that generates temperature and humidity readings, then encrypts the data using **AES-CBC**.

### 🔐 Features:
- Random sensor data generation  
- AES-128 encryption  
- IV + Ciphertext packaging  
- Secure transmission simulation  
- Proper AES padding and unpadding  

### 📤 Output:
- Original sensor reading  
- Base64 encrypted data  
- Successfully decrypted message  

---

# 🔄 Part II – IoT Device Security Lifecycle Simulation
This part models the **security lifecycle of an embedded IoT device**, consisting of:

1. Threat Modeling  
2. Secure Boot Initialization  
3. Secure Key Injection  
4. OTA Firmware Verification  
5. Secure Device Decommissioning  

Each step prints a timestamped log entry showing the device lifecycle from manufacturing to retirement.

---

# 🔒 Part III – Secure Boot Verification
This simulation demonstrates how **embedded systems verify firmware integrity** using SHA-256 hashing.

### ✔ Includes:
- Storing the original firmware hash  
- Hashing the firmware at boot  
- Comparing both hashes  
- Deciding whether booting is allowed  

### 🟢 Expected Results:
- Matching hashes → Boot Allowed  
- Different hashes → Boot Blocked (Tampering Detected)

---

# 📝 Handwritten Theoretical Answers
All theoretical questions (Q1–Q25) were written **by hand** and included in the final submission PDF as required.

---


