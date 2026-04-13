# 🖧 CCNA Project: Cisco 2960 Switch Initialization, Security Baseline & MAC Analysis

[![Cisco](https://img.shields.io/badge/Cisco-2960-1BA0D7?style=flat&logo=cisco)](https://www.cisco.com)
[![IOS](https://img.shields.io/badge/IOS-15.0(2)SE4-blue)](https://www.cisco.com)
[![CCNA](https://img.shields.io/badge/CCNA-Layer_2_Switching-005073)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna.html)

## 📋 Project Overview
This project documents a real-world **Cisco Catalyst 2960-24TT-L** switch boot sequence, hardware POST verification, initial security configuration, and Layer 2 MAC address table analysis. The capture demonstrates essential CCNA concepts including:

- Bootloader & IOS Initialization Process
- Hardware POST (Power-On Self-Test) Validation
- Cisco IOS Image Identification & Licensing (LAN Base vs. IP Base)
- Basic Switch Security Hardening (Console & Enable Secrets)
- Dynamic MAC Address Learning & CAM Table Inspection

> ⚠️ **Critical Field Note:** This project also highlights a significant operational risk (CSCuj15687) regarding the specific IOS version `15.0(2)SE4`, demonstrating real-world troubleshooting awareness.

---

## 🖥️ Hardware & Software Specifications

| Component | Detail |
| :--- | :--- |
| **Model** | Cisco WS-C2960-24TT-L |
| **Ports** | 24 x 10/100 FastEthernet, 2 x 10/100/1000 Gigabit Ethernet |
| **DRAM** | 64 MB |
| **Flash Memory** | 64 MB |
| **IOS Version** | 15.0(2)SE4 |
| **Feature Set** | `C2960-LANBASEK9-M` (LAN Base - Layer 2 Only) |
| **System Serial** | `FOC1010X104` |
| **Base MAC** | `00D0.5875.1E04` |

---

## 🔍 Project Sections (Key CCNA Learning Points)

### 1. Boot Sequence & POST Analysis
*File Reference: `boot_output.txt` (Lines 1-45)*

The boot sequence verifies hardware integrity. The **Power-On Self-Test (POST)** results confirm the switch hardware is fully operational.
