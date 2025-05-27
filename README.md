# 🛡️ SQL Injection Labs

My personal lab notes and learning journey through PortSwigger’s Web Security Academy — SQL Injection chapter.

This repository is a collection of hands-on labs I completed to explore SQL injection vulnerabilities: how to find them, exploit them, and understand their impact in real-world scenarios.

🔗 [Web Security Academy - SQL Injection](https://portswigger.net/web-security/sql-injection)

---

## ⚙️ Environment Setup

I worked on these labs in a virtual environment using:

- Kali Linux (VM on VirtualBox)
- Burp Suite Community Edition (2023.x)
- Firefox + FoxyProxy Extension

---

## 📚 What I Learned

Before diving into the labs, I took the time to study key concepts from official documentation and practical YouTube tutorials. This helped me build a solid foundation for understanding and practicing SQL injection techniques.

- What is SQL Injection?
  - Types: Classic, Union-based, Blind, Error-based, Time-based, Out-of-band
- How to detect it?
  - Testing strategies (Black Box, Grey Box)
  - Manual testing using Burp Suite
  - Analyzing server responses and input behavior from crafted payloads
- How to exploit it?
  - SQL query manipulation, UNION abuse, error messages, blind logic, delay-based extraction, etc.
- How to prevent it?
  - Use of prepared statements, stored procedures, input validation (whitelisting), input escaping, enforcing least privilege

🎥 Sources: YouTube tutorials, blog posts, OWASP documentation, and PortSwigger learning resources.

---

## 🧪 Lab Progress

### 🔹 Basic SQL Injections

- Lab 01: Retrieve hidden data using WHERE clause
- Lab 02: Login bypass via SQL injection
- Lab 03: UNION attack – identifying column count
- Lab 04: UNION attack – identifying data types
- Lab 05: UNION attack – extract data from other tables
- Lab 06: UNION attack – retrieve multiple values in a single column

### 🔹 Database Enumeration

- Lab 07: Detect DB type and version (Oracle)
- Lab 08: Detect DB type and version (MySQL / Microsoft)
- Lab 09: List DB contents – non-Oracle
- Lab 10: List DB contents – Oracle

### 🔹 Blind SQL Injection

- Lab 11: Blind SQLi with conditional responses
- Lab 12: Blind SQLi with conditional errors
- Lab 13: Blind SQLi with time delays
- Lab 14: Blind SQLi – extract info via delay
- Lab 15: Blind SQLi – out-of-band (Burp Pro)
- Lab 16: Blind SQLi – data exfil via Burp Collaborator (Burp Pro)
- Lab 17: Filter bypass using XML encoding
- Lab 18: Error-based SQL Injection

> ⚠️ Labs requiring Burp Suite Pro (e.g., Burp Collaborator) were studied theoretically if no workaround was available.

---

## 🛠️ Automation & Scripting (Coming Soon)

I plan to write Python scripts to simulate and automate certain SQLi techniques, especially for blind injection and brute-force enumeration. While manual practice is essential, scripting improves both speed and repeatability — key skills for any future Red Teamer or penetration tester.

---

## 📸 Documentation (Coming Soon)

Each lab will include:

- A markdown file detailing the exploitation steps
- Payloads used and their effects
- Key observations and learning points
- Screenshots from Burp and browser

---

## 📌 Notes

This project is for educational purposes only. All labs were conducted in a legal and controlled environment provided by PortSwigger’s academy.

---

## 🧠 Next Steps

- Complete scripting automation for blind SQLi labs
- Add vulnerability reports in Markdown format
- Expand to other vulnerability categories (e.g., XSS, CSRF, Auth Bypass)

---

Made with ☕, Burp & determination  
by [Kaouthar Belkebir](https://www.linkedin.com/in/kaouthar-belkebir)
