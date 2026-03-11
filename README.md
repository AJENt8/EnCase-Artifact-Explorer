# 🧪 EnCase Artifact Explorer — Data Leakage Investigation

> **Summary:** Completed an **EnCase Artifact Explorer forensic analysis lab**.
> The investigation focused on identifying evidence of **possible insider data exfiltration** through system artifacts, removable media, and communication traces.

---

## 🎯 Objectives

- Practice analyzing forensic artifacts using **EnCase Artifact Explorer**
- Identify evidence of **data exfiltration attempts**
- Examine **Windows system artifacts**
- Investigate **email communication**
- Analyze **removable storage device usage**
- Reconstruct **user activity through forensic artifacts**

---

## 🛠 Environment

- **Platform:** Data Leakage Case Lab
- **Forensic Tool:** EnCase Artifact Explorer

---

## 🚀 Workflow

### 1) Launch EnCase Artifact Explorer

- Opened the forensic analysis tool `encase-artifact-explorer` to parse system artifacts.

### 2) Load Evidence Image
- Loaded the provided forensic evidence image for analysis.
- Supported evidence formats include:
  - ```bash
    .E01
    .DD
    .VMDK
    
### 3) Mount Evidence in Read-Only Mode
- Mounted the evidence to ensure the integrity of forensic data. This prevents any modification of the original evidence.

### 4) Analyze System Information Artifacts
- Navigated to system configuration artifacts.
- Artifacts reviewed included:
  - Operating system details
  - Hostname
  - Installed applications
  - System configuration settings

### 5) Review User Account Artifacts
- Investigated user account information and login activity.
- Artifacts examined:
  - User profiles
  - Account creation timestamps
  - Last login activity

### 6) Investigate Network Configuration
- Examined network interface and configuration artifacts.
- Artifacts reviewed:
  - DHCP assigned IP addresses
  - Network adapters
  - Possible network connections

### 7) Analyze Email Artifacts
- Investigated artifacts related to email communication.
- Artifacts examined:
  - Email client usage
  - Mailbox storage locations
  - Possible communication with external parties

### 8) Identify External Storage Devices
- Analyzed artifacts related to removable media connections.
- Artifacts included:
  - USB device serial numbers
  - Device vendor information
  - Connection timestamps

### 9) Examine File System Metadata
- Reviewed file system artifacts to identify file access activity.
- Metadata reviewed:
  - File timestamps
  - File access patterns
  - Directory navigation activity

### 10) Analyze Network Drive Activity
- Investigated activity involving corporate network drives.
- Artifacts examined:
  - Mapped drives
  - Accessed directories
  - File interaction activity

### 11) Review Optical Media Artifacts
- Checked artifacts related to CD/DVD burning.
- Artifacts included:
  - Disc creation activity
  - Burning software usage
  - Files written to optical media


### 12) Investigate Deleted Files
- Reviewed deleted artifacts through Windows recycle bin analysis.
- Artifacts examined:
  - Deleted file metadata
  - Deletion timestamps
  - Potential attempts to remove evidence

### 13) Generate Activity Timeline
- Created a forensic timeline to reconstruct user behavior.
- Timeline analysis correlates:
  - File activity
  - Device connections
  - User login activity
  - Application usage

---

## 🧠 Skills Demonstrated
- Digital Forensics Investigation
- Artifact Analysis with EnCase Artifact Explorer
- Windows System Artifact Examination
- Removable Media Forensics
- Email Artifact Analysis
- File System Metadata Analysis
- Insider Threat Investigation
- Timeline Reconstruction

  
