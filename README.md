**NETWORKWALKS-B083-WK-4-WEBAPPLICATION PENETRATION TESTING ASSESSMENT**
--

![Cybersecurity](https://img.shields.io/badge/Skill-Cybersecurity-red)
![Virtualbox](https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0078D7?logo=virtualbox)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-v2026.2-black?logo=kalilinux)
![Linux](https://img.shields.io/badge/Skill-Linux-E95420)
![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-crimson?logo=hackthebox)
![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-darkslategray)
![Author](https://img.shields.io/badge/Author-grey)
![Author](https://img.shields.io/badge/ANJU%20-red)






<h2 align="center">Mediroza hospital Penetration Testing Report</h2>

**📌 Project Information**

| 🧩 Component | ⚙️ Detail |
| :--- | :--- |
| Program | cybersecurity Internship at Networkwalks |
| Week | 04|
|Batch |B083|
| 🐉Phases Covered |Phase 1: 👣Reconnaissance & Footprinting  |                	
|           |Phase 2: Scanning & Network Discovery |
|           |Phase 3:⚔️ Penetration Testing |
| 🌐 Target | Medirozahospital |
|Assessment type| Web Application security analysis by Black-box penetration testing|
| 🔐Permission Secured | Yes |
| 🚪 Repository | Git hub |
----------------------------


**1.Liability Desclaimer:**
-----------------

I have performed these activities only on systems and devices where I had secured written permission or on devices/systems that I own myself.

All materials are provided for educational and research purposes only. Do not use anything from this report to break the law.

The instructor, authors, and Networkwalks are not responsible for misuse of the information provided in this report. Every action taken using this knowledge is the user's own responsibility.

Unauthorized access to computer systems can result in criminal charges, financial penalties, loss of employment, and other legal consequences.


📌Project overview
-
This project alligned with Healthcare  Mediroza General Hospital with explicit permission by this organisation .Mediroza General Hospital brings together experienced specialists, modern diagnostics and round-the-clock emergency services under one roof.It has served Johannesburg since 2003.We have permission to check the security of this web application by VAPT .During the Penetration testing it is prohibited to disclose the weakness or Vulnerabilities or any confidential files ,information of the organisation.It is only for learning purpose .We have 4 milestones to complete.
- M1:-Authentication process 
- M2:-Data extraction through pdf locked
- M3:-Confidential Database Information
- M4:-Penetration testing Report

![Screenshot](Screenshot-1)

Tools🧰
--
Step 1 :- Go to webservice the interface image is above mentioned
Step 2:-Now go to patient portal .
step 3:-As we have no credential to login lets use SQL based command .The login page returned different responses for invalid usernames and valid usernames with an incorrect password.

This behavior allowed confirmation of whether a username existed.
Step 4 :- Now added another hyper sql command to login
Step 5 :- These are reports of some patients .
Step 6:- Downloaded it and we will try to open it by carcking password .
Step 7:- Go to Networkwalks and use these two tools:---
 - Networkwalks Hash-Calculator
- Networkwalks Password Cracker
(a) Opening Hash-calculator then I Uploaded the locked PDF to the Hash Calculator to get the hash lines. The Hash Calculator supports MD5, SHA-1, SHA-256, SHA-384, and SHA-512 or extract a crackable hash from dedicated file .
(b) Now paste the hash lines in NW password cracker tools .


