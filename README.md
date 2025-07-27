# 🔐 VAPT on a Login Portal – Internship Project

### 👨‍💻 Author: Tarun Roshan A D  
### 🏢 Internship: Pentester Intern @ Deltaware  
### 🗓️ Duration: 1 Month  
### ⚙️ Environment: DVWA (on localhost)

---

## 📌 Project Overview

This project demonstrates a practical Vulnerability Assessment and Penetration Testing (VAPT) of a login portal using DVWA. The goal was to identify and exploit common web vulnerabilities in a controlled lab setup.

---

## 🧪 Vulnerabilities Exploited

| Vulnerability | Description |
|---------------|-------------|
| SQL Injection | Bypassed login using `?id=1 OR 1=1` |
| XSS | Injected `<img src='sef' onerror=alert('xss')>` |
| LFI | Accessed `/etc/passwd` directly via file parameter |

---

## 🛠️ Tools Used

- DVWA
- Burp Suite
- Kali Linux
- Firefox
- Screen Recorder

---

## 📄 Deliverables

- [✔️ Report (DOCX)]
- 🎥 Screen Recording (attached separately)

---

## ⚠️ Disclaimer

This project was conducted strictly for educational purposes in a legal and safe lab environment. DVWA was used to simulate vulnerable systems. Do **not** attempt unauthorized access on real-world systems.
