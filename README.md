 Live Volatile Data Acquisition & Integrity Verification (VM Forensics)

✨ Project Overview

This project demonstrates forensically sound volatile data acquisition and integrity verification performed entirely within a Virtual Machine environment. The goal was to execute a live system triage by capturing critical volatile artifacts (System Memory/RAM) and non-volatile artifacts (Registry Hives) without relying on external physical media (USB).

This approach ensures rapid, forensically sound data collection, linking core Cybersecurity and Digital Forensics principles to a Criminological context.

 🔬 Evidence Acquisition & Verification

Tools Used: FTK Imager (Acquisition), Volatility Framework (Analysis/Planned Next Steps)

| Artifact | File Name | Integrity Hash (SHA1) | Acquisition Date/Time (IST) |

| System RAM Dump | VM_RAM_Capture.Mem | [SHA1_HASH_REDACTED_A] | [DATE_TIME_REDACTED] |
| Registry Hives | Registry_Hives.zip | [SHA1_HASH_REDACTED_B] | [DATE_TIME_REDACTED] |
| Final Archive | Evidence.7z | [SHA1_HASH_REDACTED_B] | [DATE_TIME_REDACTED] |

Evidence Integrity: All acquired evidence was hashed using FTK Imager and verified for integrity, confirming "No bad blocks found in image." The hash values shown above were computed upon creation and verified upon archiving. The specific cryptographic hashes are redacted for security, but were logged for chain of custody.Chain of Custody: Detailed in the accompanying Evidence_Manifest.pdf.
