# REU_4n6-PLC: Digital Forensics and Reverse Engineering for PLCs

Welcome to the **REU_4n6-PLC** repository. This project is dedicated to the research and development of digital forensics, reverse engineering methodologies, and security analysis frameworks for Programmable Logic Controllers (PLCs) and Industrial Control Systems (ICS).

This repository serves as a centralized hub for undergraduate researchers (REU interns) to collaborate, share scripts, document findings, and learn applied cybersecurity practices in industrial environments.

---
## 📖 REU Interns Study Guide

### 1. Ghidra
I recommend two different approaches for studying Ghidra.

#### 1.1. Direct Installation Method
Install the software directly on your system. I used version 12.0 for my work. Install it in your designated directory, run the application, and download the `.app` files from the GitHub repository linked below. Try analyzing them using the **ARMv5t Little-endian** setting. 

> ⚠️ **Note:** The goal here is simply to verify that everything runs properly and to examine the initial results; there is no need for an in-depth analysis at this stage.

* **Repository:** [REU_4n6-PLC](https://github.com/dndusdndus12/REU_4n6-PLC)

#### 1.2. API Utilization via `pyghidra`
Install Python and explore using the Ghidra API through `pyghidra`. Afterward, see if you can utilize `pyghidra` to extract any meaningful analysis from the `.app` files you downloaded in the previous step.

---

### 2. Wireshark
Learn how to use Wireshark to analyze and utilize the UMAS protocol.

#### 2.1. DFRWS Challenge
Download the network packet traces from the following DFRWS Challenge repository:
* **Repository:** [dfrws2023-challenge](https://github.com/dfrws/dfrws2023-challenge/)

**Your Task:** Develop and apply a custom Lua script that can properly recognize the UMAS protocol within these packet traces.

> 💡 **Recommendation:** I highly encourage you to utilize and improve upon the existing Lua scripts available in this directory: `REU_4n6-PLC/src`.

---

### 📚 Reading Materials
The following papers are listed in reverse chronological order (newest to oldest). It is **highly recommended** that you read them starting from the oldest to understand the progression and flow of the research, taking your time to digest each one thoroughly.

1. *Oops, It Halted Again: Exploiting PLC Memory for Fun and Profit in Industrial Control Systems*
2. *Gadgets of gadgets in industrial control systems: Return oriented programming attacks on plcs*
3. *How are industrial control systems insecure by design? a deeper insight into real-world programmable logic controllers*
4. *PEM: Remote forensic acquisition of PLC memory in industrial control systems*
5. *Overshadow plc to detect remote control-logic injection attacks*

---
