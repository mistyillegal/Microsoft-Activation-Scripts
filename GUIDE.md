# GUIDE.md - Complete Guide for Microsoft Activation Script (MAS)

**Latest Version:** 2.6 (June 2026)

This is a full step-by-step guide on how to activate **Windows 10**, **Windows 11**, and **Microsoft Office** using MAS.

## Table of Contents
1. [What is MAS?](#what-is-mas)
2. [What's Inside the Archive](#whats-inside)
3. [System Requirements](#system-requirements)
4. [Antivirus Warning](#antivirus-warning)
5. [How to Activate Windows 10 / Windows 11](#activate-windows)
6. [How to Activate Microsoft Office](#activate-office)
7. [Available Activation Methods](#activation-methods)
8. [Troubleshooting Common Errors](#troubleshooting)
9. [FAQ](#faq)

---

## What is MAS?

**Microsoft Activation Script (MAS)** is a free, open-source script that allows you to **activate Windows 10**, **Windows 11**, and **Microsoft Office** without needing an official product key.

It supports HWID, KMS, and Ohook activation methods.

---

## What's Inside the Archive

- `mas.exe` – Main executable file
- `Readme.txt` – Additional information

---

## System Requirements

- Windows 10 (version 1607 or newer)
- Windows 11 (all versions)
- Internet connection (for initial activation)
- Administrator privileges

---

## ⚠️ Important Antivirus Warning

> **Most antiviruses (Windows Defender, Avast, Kaspersky, etc.) will detect and remove `mas.exe`.**

**What to do:**
1. **Temporarily disable** real-time protection before running the script.
2. Add the folder containing `mas.exe` to antivirus exclusions.
3. Re-enable protection after successful activation.

Without disabling antivirus, the script may not run.

---

## How to Activate Windows 10 / Windows 11

1. Download the latest `mas.zip` from the [Releases](https://github.com/.../releases) page
2. Extract the archive to any folder
3. **Disable your antivirus** (see warning above)
4. Right-click on `mas.exe` → **Run as administrator**
5. In the menu, select:
   - `1` → **HWID Activation** (Recommended - Permanent)
   - `2` → **KMS Activation**
6. Wait for the process to complete
7. Restart your computer

Your Windows should now be fully activated and the "Activate Windows" watermark removed.

---

## How to Activate Microsoft Office

1. Run `mas.exe` as administrator
2. Select option `3` → **Office Activation**
3. Choose the desired method (Ohook is recommended)
4. Wait for completion

Supported versions: Office 365, Office 2021, Office 2024.

---

## Activation Methods

| Method     | Duration         | Recommendation       | Notes                        |
|------------|------------------|----------------------|------------------------------|
| HWID       | Permanent        | ★★★★★ (Best)         | Digital License              |
| KMS        | 180 days         | ★★★★                 | Auto-renews                  |
| KMS38      | Long-term        | ★★★★                 | For Windows                  |
| Ohook      | Permanent        | ★★★★★                | For Microsoft Office         |

---

## Troubleshooting Common Errors

- **0xC004F074** → Check internet connection, disable VPN
- **0xC004F213** → Run the script as Administrator
- **Antivirus deletes file** → Add to exclusions
- **Script doesn't start** → Run as Administrator
- **After hardware change** → Run HWID activation again

---

## FAQ

**Q:** Do I need a Windows product key?  
**A:** No. The script activates Windows **without** a product key.

**Q:** Will activation be lost after Windows Update?  
**A:** Usually not. HWID activation is very stable.

**Q:** Is it safe to use?  
**A:** The script is open-source and widely used.

**Q:** Does it work on Windows 11 24H2?  
**A:** Yes, fully supported.

---

If you have any issues, please open an **Issue** in this repository.

**Good luck with activation!**