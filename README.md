 Live Volatile Data Acquisition & Integrity Verification (VM Forensics)

 📌 Project Overview

This project demonstrates forensically sound volatile data acquisition and integrity verification performed entirely within a Virtual Machine (VM) environment. The goal was to execute a live system triage by capturing critical volatile artifacts (System Memory/RAM) and non-volatile artifacts (Registry Hives) without relying on external physical media (USB).

This approach ensures rapid, forensically sound data collection, linking core Cybersecurity and Digital Forensics principles to a Criminology context.

---

 🔬 Evidence Acquisition & Verification

Tools Used: FTK Imager (Acquisition), Volatility Framework (Analysis/Planned Next Steps)

| Artifact | File Name | Integrity Hash (SHA1) | Acquisition Date/Time (IST) |

| System RAM Dump | VM_RAM_Capture.Mem | 9ABCFF8E9BDB5446F54147FF995144353B86685 | 2025-10-03, 14:45:56 |
| Registry Hives | Registry_Hives.zip | D3752625B069C53C3B8AE84BB49E03907B7CFEB | 2025-10-03, 14:48:00 |
| Final Archive | Evidence.7z | D3752625B069C53C3B8AE84BB49E03907B7CFEB | 2025-10-03, 14:50:00 |

Evidence Integrity: All acquired evidence was hashed using FTK Imager and verified for integrity, confirming "No bad blocks found in image"*. The hash values shown above were computed upon creation and verified upon archiving.
Chain of Custody: Detailed in the accompanying Evidence_Manifest.pdf.

---

 🔗 Project Documentation

Evidence_Manifest.pdf: Formal log of all acquired evidence items, hash values, file sizes, and Chain of Custody (CoC) details.
FTK_Acquisition_Log.txt: Raw output log from the forensic tool, confirming successful completion and hash calculations.
Proof_Screenshot.pdf: Visual confirmation of hash calculation 

 
