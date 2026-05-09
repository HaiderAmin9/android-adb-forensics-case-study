# 📱 Android Logical Forensics using ADB & Autopsy

## 🔍 Overview
This project presents a complete **Android digital forensic investigation workflow** involving logical data acquisition, evidence preservation, integrity verification, and forensic analysis.

The investigation was conducted using **Android Debug Bridge (ADB)** for data extraction and **Autopsy 4.22.1** for forensic analysis, following standard digital forensic principles such as data integrity, repeatability, and non-intrusiveness.

---

## 🎯 Objectives
- Perform logical acquisition from an Android device using ADB  
- Extract user and system data securely  
- Preserve forensic integrity using SHA-256 hashing  
- Analyze extracted data using Autopsy  
- Identify key artifacts (SMS, images, app data, metadata)  

---

## 📱 Device Information
- **Device:** Tecno Spark 20 Pro+  
- **Android Version:** 14  
- **Serial Number:** 115333741R033668  
- **IMEI:** 356237361627845    
- **Case ID:** forensic_case  

---

## 🧰 Tools & Technologies
- Android Debug Bridge (ADB)  
- Android SDK Platform Tools  
- Android Backup Extractor (ABE)  
- Autopsy 4.22.1  
- Windows Certutil (SHA-256 hashing)  
- Windows Command Prompt  

---

## ⚙️ Methodology

### 1. Environment Setup
- Installed Android SDK Platform Tools
- Configured system environment variables for ADB access

### 2. Device Preparation
- Enabled Developer Options
- Activated USB Debugging on target device

### 3. Device Connection
- Verified device connectivity using:
```bash
adb devices
