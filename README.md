# HunterM - macOS Forensics 🕵️‍♂️

![Banner](banner.png)

### A powerful macOS DFIR artifact collection tool for forensic analysis.

HunterM is a **digital forensics tool** designed to collect and analyze **key macOS forensic artifacts**. It is useful for **incident response, threat hunting, and compromise assessments**.

---

## 🚀 **Features**
- ✅ Collects **Login Items, Network Connections, Extended Zsh History**
- ✅ Retrieves **System Information** (OS, kernel, timezone)
- ✅ Extracts **Browser History** (Safari, Chrome, Firefox)
- ✅ Lists **Installed Applications**
- ✅ Exports collected artifacts into **structured reports**
- ✅ **No dependencies** (except `colorama` for colored output)

## 📌 Collected Artifacts

| **Artifact**            | **Description** |
|-------------------------|---------------------------------------------|
| **Login Items**         | Applications that start automatically at login |
| **Network Connections** | Active network connections (ESTABLISHED state) |
| **Zsh History**         | Extended shell history with timestamps |
| **System Information**  | OS version, kernel details, timezone |
| **Browser History**     | Safari, Chrome, and Firefox visited sites |
| **Installed Applications** | Lists all installed applications |

---
## ⚡ Usage

Python HunterM.py -e output_directory

