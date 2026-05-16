# Forensic Imaging — Scoping Questionnaire
**Xservus Limited | Confidential — For Internal and Client Use**
*Complete prior to engagement confirmation. All fields should be answered where known; mark unknown items as `TBC` rather than leaving blank.*

---

## Section 1 — Engagement Purpose & Legal Authority

> Determines the evidential standard required, chain of custody obligations, and whether legal admissibility is a hard requirement.

| # | Question | Response |
|---|----------|----------|
| 1.1 | What is the primary purpose of this imaging? | ☐ Civil litigation &nbsp; ☐ Criminal investigation &nbsp; ☐ HR/disciplinary &nbsp; ☐ Regulatory/compliance &nbsp; ☐ Malware/incident analysis &nbsp; ☐ Internal audit &nbsp; ☐ Insurance claim &nbsp; ☐ Other: ___ |
| 1.2 | Is this image likely to be used as evidence in legal proceedings (civil or criminal)? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 1.3 | Has legal counsel been engaged? If yes, who is the instructing solicitor or legal team? | |
| 1.4 | Is there a court order, preservation notice, or legal hold in place? | ☐ Yes (attach) &nbsp; ☐ No &nbsp; ☐ Pending |
| 1.5 | Who has authority to authorise access to the device? (e.g. device owner, employer, court) | |
| 1.6 | Is the device subject to any regulatory framework? (e.g. FCA, ICO/GDPR, NIS2, HIPAA, defence supply chain) | |
| 1.7 | Has the subject (individual) been informed? Is informed consent required? | ☐ Yes, informed &nbsp; ☐ No, covert &nbsp; ☐ TBC |
| 1.8 | Is there a data protection consideration — does the image likely contain personal data of third parties? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 1.9 | What jurisdiction applies? (England & Wales / Scotland / NI / EU / Other) | |
| 1.10 | Is PACE (Police and Criminal Evidence Act) compliance required, or equivalent overseas standard? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unsure |

---

## Section 2 — Device Details

> Determines tooling, bootability, write-blocker type, and acquisition method.

| # | Question | Response |
|---|----------|----------|
| 2.1 | How many devices are in scope? | |
| 2.2 | Device form factor | ☐ Desktop &nbsp; ☐ Laptop &nbsp; ☐ All-in-one &nbsp; ☐ Server &nbsp; ☐ Mac (specify model) &nbsp; ☐ Tablet &nbsp; ☐ Other: ___ |
| 2.3 | Make and model (if known) | |
| 2.4 | Operating system (if known) | ☐ Windows (version: ___) &nbsp; ☐ macOS (version: ___) &nbsp; ☐ Linux (distro: ___) &nbsp; ☐ Unknown |
| 2.5 | Is the device currently powered on or off? | ☐ On (live) &nbsp; ☐ Off &nbsp; ☐ Unknown |
| 2.6 | If powered on — is a live RAM capture required before shutdown? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Assess on arrival |
| 2.7 | Is the OS drive encrypted? | ☐ Yes — BitLocker &nbsp; ☐ Yes — FileVault &nbsp; ☐ Yes — LUKS &nbsp; ☐ Yes — VeraCrypt or unknown product &nbsp; ☐ No &nbsp; ☐ Unknown |
| 2.8 | If encrypted — is the decryption key, recovery key, or credential available? | ☐ Yes (document separately) &nbsp; ☐ No &nbsp; ☐ Unknown |
| 2.9 | Is a BIOS/UEFI password set? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 2.10 | Is Secure Boot enabled? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 2.11 | Storage interface type (if known) | ☐ SATA HDD &nbsp; ☐ SATA SSD &nbsp; ☐ NVMe M.2 &nbsp; ☐ eMMC (soldered) &nbsp; ☐ Apple T2/T-series (non-removable) &nbsp; ☐ Unknown |
| 2.12 | Approximate storage capacity | ☐ <256 GB &nbsp; ☐ 256 GB–1 TB &nbsp; ☐ 1–4 TB &nbsp; ☐ >4 TB &nbsp; ☐ Unknown |
| 2.13 | Are there external drives, USB sticks, or memory cards also in scope? | ☐ Yes (quantity/type: ___) &nbsp; ☐ No |
| 2.14 | Is there cloud storage (OneDrive, iCloud, Google Drive, Dropbox) in scope? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ TBC |
| 2.15 | Are mobile devices (phones/tablets) in scope? | ☐ Yes (handled separately) &nbsp; ☐ No |

---

## Section 3 — Physical Access & Location

> Determines logistics, travel, safe working conditions, and whether equipment can leave the premises.

| # | Question | Response |
|---|----------|----------|
| 3.1 | Where is the device currently located? | ☐ Client premises (address: ___) &nbsp; ☐ Residential address &nbsp; ☐ Third-party/co-location &nbsp; ☐ Already with examiner |
| 3.2 | Can the device be transported to our forensic facility? | ☐ Yes &nbsp; ☐ No — must remain on-site &nbsp; ☐ Requires approval |
| 3.3 | If the device must remain on-site, is a suitable clean working area available? (desk, power, adequate lighting) | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 3.4 | Is the site subject to physical access controls requiring pre-clearance? (e.g. security passes, visitor escort, DV clearance) | ☐ Yes (detail: ___) &nbsp; ☐ No |
| 3.5 | Are there any CCTV, recording, or monitoring restrictions at the location relevant to the examiner? | |
| 3.6 | Will a client representative need to be present during the imaging? | ☐ Yes (who: ___) &nbsp; ☐ No &nbsp; ☐ Preferred |
| 3.7 | Are there health and safety considerations at the location? (industrial site, restricted access, etc.) | |
| 3.8 | Is mains power reliably available? Is a UPS required for prolonged acquisitions? | ☐ Mains available &nbsp; ☐ Generator/unreliable &nbsp; ☐ UPS needed |
| 3.9 | Is there a network connection available on-site for remote acquisition or tool download? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Air-gapped required |

---

## Section 4 — Acquisition Scope & Tasking

> Determines whether a full disk image, targeted collection, or triage is appropriate, and sets realistic time expectations.

| # | Question | Response |
|---|----------|----------|
| 4.1 | Is a full forensic disk image (sector-by-sector) required, or is targeted/logical acquisition acceptable? | ☐ Full image (sector-by-sector) &nbsp; ☐ Logical/targeted &nbsp; ☐ Triage first, then decide |
| 4.2 | Is recovery of deleted files or unallocated space analysis in scope? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ TBC |
| 4.3 | Is analysis of the image in scope, or imaging only? | ☐ Imaging only &nbsp; ☐ Imaging + analysis &nbsp; ☐ TBC |
| 4.4 | If analysis is in scope, what is the primary focus? | ☐ Malware/threat actor activity &nbsp; ☐ Data exfiltration/DLP &nbsp; ☐ User activity timeline &nbsp; ☐ Specific file/document recovery &nbsp; ☐ Email/comms &nbsp; ☐ Internet history &nbsp; ☐ Anti-forensics/wiping indicators &nbsp; ☐ Other: ___ |
| 4.5 | Are there specific date ranges, users, or file types of interest? | |
| 4.6 | Is keyword searching required? If so, are keywords already defined? | ☐ Yes (attach keyword list) &nbsp; ☐ No &nbsp; ☐ TBC |
| 4.7 | Is there a requirement to produce a timeline of activity? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ TBC |
| 4.8 | Are there any known indicators of compromise (IOCs) to hunt for? | ☐ Yes (attach IOC list) &nbsp; ☐ No |
| 4.9 | Is volatile data capture required? (running processes, network connections, registry hives in memory) | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Device is already off |
| 4.10 | Is log acquisition from external sources also required? (SIEM, firewall, AD, cloud) | ☐ Yes (detail: ___) &nbsp; ☐ No |

---

## Section 5 — Chain of Custody & Evidential Handling

> Only relevant if legal admissibility is a consideration, but good practice regardless.

| # | Question | Response |
|---|----------|----------|
| 5.1 | Has the device already been accessed or powered on since the incident? By whom? | |
| 5.2 | Has any data been copied from the device already? | ☐ Yes (detail: ___) &nbsp; ☐ No &nbsp; ☐ Unknown |
| 5.3 | Who currently has custody of the device, and how long have they had it? | |
| 5.4 | Is a formal chain of custody log required from point of collection? | ☐ Yes &nbsp; ☐ No |
| 5.5 | Should the original device be sealed/bagged after imaging? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Client to retain unsealed |
| 5.6 | Where should the forensic image be stored once acquired? | ☐ Examiner secure storage &nbsp; ☐ Client-provided encrypted storage &nbsp; ☐ Cloud (specify: ___) &nbsp; ☐ TBC |
| 5.7 | How many copies of the image are required? (working copy + evidence master) | |
| 5.8 | What hash algorithm is required for integrity verification? | ☐ MD5 &nbsp; ☐ SHA-1 &nbsp; ☐ SHA-256 (recommended) &nbsp; ☐ SHA-256 + MD5 (belt and braces) |
| 5.9 | Is the image to be encrypted at rest? If so, what key management process applies? | |

---

## Section 6 — Timelines & Urgency

| # | Question | Response |
|---|----------|----------|
| 6.1 | Is this a live incident requiring immediate response? | ☐ Yes — P1/emergency &nbsp; ☐ No — planned &nbsp; ☐ Urgent but not emergency |
| 6.2 | What is the deadline for image acquisition? | |
| 6.3 | What is the deadline for any analysis output? | |
| 6.4 | Is there a court or regulatory deadline driving the timeline? | ☐ Yes (date: ___) &nbsp; ☐ No |
| 6.5 | What are the working hours constraints for on-site work? | ☐ Business hours only &nbsp; ☐ Out of hours required &nbsp; ☐ Flexible |

---

## Section 7 — Deliverables & Reporting

| # | Question | Response |
|---|----------|----------|
| 7.1 | What deliverables are required? | ☐ Forensic image file(s) only &nbsp; ☐ Exhibit notes &nbsp; ☐ Examination report &nbsp; ☐ Expert witness statement &nbsp; ☐ Executive summary &nbsp; ☐ Technical timeline &nbsp; ☐ Other: ___ |
| 7.2 | What image format is required? | ☐ E01/EWF (EnCase) &nbsp; ☐ AFF4 &nbsp; ☐ Raw/dd &nbsp; ☐ VMDK/VHD (virtualisation) &nbsp; ☐ No preference |
| 7.3 | Will the examiner be required to give oral evidence or be cross-examined? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 7.4 | What classification/handling marking should apply to outputs? | ☐ TLP:RED &nbsp; ☐ TLP:AMBER &nbsp; ☐ TLP:GREEN &nbsp; ☐ OFFICIAL &nbsp; ☐ Client-defined: ___ |
| 7.5 | Who is the authorised recipient of the final report and image? | |

---

## Section 8 — Examiner & Resource Requirements

| # | Question | Response |
|---|----------|----------|
| 8.1 | Does the examiner require any specific clearance level? (e.g. SC, DV, BPSS) | ☐ Yes (level: ___) &nbsp; ☐ No |
| 8.2 | Are there specific tool or platform requirements from the client or instructing party? (e.g. FTK, Cellebrite, Magnet AXIOM) | |
| 8.3 | Is a second examiner or witness required to be present during acquisition? | ☐ Yes &nbsp; ☐ No |
| 8.4 | Will the client provide any technical assistance on-site? (e.g. to disable BitLocker, provide credentials) | ☐ Yes &nbsp; ☐ No &nbsp; ☐ TBC |
| 8.5 | Are there any conflicts of interest that should be declared? | |

---

## Section 9 — Known Complicating Factors

> Flag anything that may affect tooling choices, acquisition method, or time estimates.

| # | Question | Response |
|---|----------|----------|
| 9.1 | Is there any known anti-forensics activity suspected? (wiping, encryption, timestomping) | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Unknown |
| 9.2 | Is the device part of a domain or MDM-managed environment? | ☐ Yes (detail: ___) &nbsp; ☐ No &nbsp; ☐ Unknown |
| 9.3 | Is the device a corporate asset or personally owned? | ☐ Corporate &nbsp; ☐ Personal (BYOD) &nbsp; ☐ Unknown |
| 9.4 | Is there any known malware, ransomware, or active compromise on the device? | ☐ Yes &nbsp; ☐ No &nbsp; ☐ Suspected |
| 9.5 | Has the device been network-isolated already? | ☐ Yes &nbsp; ☐ No — should it be? |
| 9.6 | Are there hardware security modules, smart cards, or TPM considerations? | |
| 9.7 | Is the device a virtual machine? | ☐ Yes (hypervisor: ___) &nbsp; ☐ No &nbsp; ☐ Unknown |
| 9.8 | Any other known constraints, sensitivities, or information the examiner should be aware of before attending? | |

---

## Scoping Summary (Examiner Completion)

| Field | Value |
|-------|-------|
| Engagement reference | |
| Client name | |
| Instructed by | |
| Date questionnaire completed | |
| Completed by | |
| Estimated acquisition time | |
| Estimated analysis time | |
| Recommended image format | |
| On-site or lab-based? | |
| Live or dead acquisition? | |
| Evidential standard required | |
| Identified risks / flags | |
| Approved to proceed? | ☐ Yes &nbsp; ☐ No — further info required |

---
