# 🛡️ Maloy Roy Orko

### Researcher · Penetration Tester · Bug Hunter · Ethical Hacker · CTF Player

<p align="center">
  <a href="mailto:maloyroyorkooo@gmail.com">
    <img src="https://img.shields.io/badge/Email-maloyroyorkooo%40gmail.com-informational?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/maloyroyorko">
    <img src="https://img.shields.io/badge/LinkedIn-Maloy%20Roy%20Orko-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Maloyroyorko">
    <img src="https://img.shields.io/badge/GitHub-Maloyroyorko-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://websecurityinsights.my.id">
    <img src="https://img.shields.io/badge/Website-Web%20Security%20Insights-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/>
  </a>
</p>

---

## 👋 About Me

I am **Maloy Roy Orko**, an aspiring security researcher and penetration tester focused on offensive security, vulnerability research, and application security.

**Learning New Fields & Strategies Since 2019.** 💻👨‍💻

My primary interests include:

* 🌐 Web Application Security
* 🔐 API & GraphQL Security
* 🛡️ Vulnerability Assessment & Penetration Testing
* 🐛 Vulnerability Research & CVE Discovery
* 🔑 Authentication & JWT Security
* 📱 Mobile Application Security
* 🕵️ OSINT & Security Research
* 🏴‍☠️ CTF & Offensive Security

I enjoy breaking applications in controlled environments, manually validating vulnerabilities, developing reproducible proof-of-concepts, documenting technical findings, and sharing security knowledge.

---

# 🚀 Featured Projects

## 🔴 DVGA — GraphQL Application Security Assessment

**Damn Vulnerable GraphQL Application**

**Black-Box VAPT / DAST · 29 Aug 2026 – 3 Sep 2026**

Conducted a **6-day black-box Vulnerability Assessment and Penetration Testing engagement** against DVGA, focusing on GraphQL, API, authentication, authorization, injection, and application security.

### Assessment Results

* 🔴 **13 confirmed vulnerabilities**
* 🔥 **6 Critical**
* 🟠 **6 High**
* 🟡 **1 Medium**
* **Highest CVSS v3.1:** 9.8
* **Average CVSS:** 8.2

### Key Findings

* JWT Signature Validation Bypass
* GraphiQL Protection Bypass
* Missing Login Rate Limiting
* OS Command Injection
* SSRF
* SQL Injection
* Stored XSS
* GraphQL Resource Exhaustion
* Authentication & Authorization weaknesses

### Methodology & Tooling

**Methodologies:** OWASP WSTG · OWASP API Security principles

**Tools:**
`Burp Suite` `OWASP ZAP` `InQL` `ffuf` `Katana` `Wapiti` `SQLMap` `GraphQL Voyager` `graphw00f` `JWT Tools` `Browser DevTools`

📂 **Repository:**
https://github.com/Maloyroyorko/DVGA-application-security-assessment

---

## 🟠 crAPI — API Security Assessment

**Completely Ridiculous API**

**Black-Box VAPT / DAST · 24 May 2026 - 30 May 2026**

Performed a **7-day black-box API security assessment** against crAPI, combining manual penetration testing with automated security testing.

### Assessment Results

* 🔴 **18 confirmed findings**
* 🔥 **2 Critical**
* 🟠 **14 High**
* 🟡 **2 Medium**
* 📄 **129-page technical report**

### Key Findings

* Broken Object Level Authorization (BOLA / IDOR)
* JWT Authentication Bypass
* JWT `None` Algorithm Attack
* SQL Injection
* NoSQL Injection
* SSRF
* Authentication & Authorization weaknesses

### Methodology & Tooling

**Methodologies:** OWASP WSTG · OWASP API Security Top 10

**Tools:**
`Burp Suite` `OWASP ZAP` `Wapiti` `Katana` `ffuf` `Browser DevTools`

📂 **Repository:**
https://github.com/Maloyroyorko/crAPI-application-security-assessment

---

## 🟢 IP OSINT Toolkit

An open-source **IP address OSINT toolkit** developed for cybersecurity research, reconnaissance, and intelligence gathering.

### Capabilities

* 🌐 IP address intelligence
* 📍 IP geolocation
* 🔎 Basic & advanced IP OSINT
* 🗺️ Mass IP location tracing
* 📌 Forward & reverse geocoding
* 🕵️ OSINT data collection
* 🔍 Infrastructure reconnaissance

The project was built as a practical security research utility for understanding publicly available IP intelligence and reconnaissance workflows.

📂 **Repository:**
https://github.com/Maloyroyorko/IP-OSINT-Toolkit

---

# 🐛 Vulnerability Research

My vulnerability research focuses on discovering, manually validating, documenting, and responsibly disclosing security vulnerabilities.

### Research Areas

`SQL Injection` · `XSS` · `RCE` · `CSRF` · `IDOR` · `Authentication` · `Authorization` · `File Upload` · `Information Disclosure` · `DoS` · `CWE-307`

### Published CVE Records

🐛 Vulnerability Research & CVE Records

My vulnerability research focuses on identifying, validating, documenting, and responsibly disclosing security vulnerabilities across web applications and software systems.

📊 Research Summary
Metric	Result
🐛 CVE Records	28
🔎 Primary Researcher	Maloy Roy Orko
🌐 Primary Focus	Web Application Security
💉 Major Vulnerability Classes	SQL Injection · XSS · Authentication · Authorization · CSRF · File Upload
🧪 Research Approach	Manual Testing · Vulnerability Validation · PoC Development
📚 Documentation	CVE Records · Technical Write-ups · Security Advisories
🔬 Comprehensive CVE Mapping Matrix
CVE ID	Vendor	Product / Software	Vulnerability Type	Vulnerable Component	Discovered By / Advisory
CVE-2025-9848	ScriptAndTools	Real Estate Management System 1.0	Execution After Redirect (EAR)	/admin/userlist.php	Maloy Roy Orko
CVE-2025-9847	ScriptAndTools	Real Estate Management System 1.0	Unrestricted File Upload	/register.php (uimage)	Maloy Roy Orko
CVE-2025-9651	shafhasan	chatbox 1.0	SQL Injection	/chat.php (user_id)	Maloy Roy Orko
CVE-2025-6329	ScriptAndTools	Real Estate Management System 1.0	Authorization Bypass	/admin/userdelete.php	Maloy Roy Orko
CVE-2025-5128	ScriptAndTools	Real-Estate-website-in-PHP 1.0	SQL Injection	/admin/ (Password)	Maloy Roy Orko
CVE-2025-4067	ScriptAndTools	Online-Travling-System 1.0	Improper Access Control	/admin/viewpackage.php	Maloy Roy Orko
CVE-2025-4066	ScriptAndTools	Online-Travling-System 1.0	Broken Authentication	/admin/login.php	Maloy Roy Orko
CVE-2025-4065	ScriptAndTools	eCommerce-website-in-PHP 3.0	Information Disclosure	/admin/subscriber-csv.php	Maloy Roy Orko
CVE-2025-4064	ScriptAndTools	Online-Travling-System 1.0	Improper Access Control	/admin/viewenquiry.php	Maloy Roy Orko
CVE-2025-3975	Tutorials-Website	Employee Management System 1.0	SQL Injection	/admin/login.php	Security Community
CVE-2025-3557	ScriptAndTools	eCommerce-website-in-PHP 3.0	Cross-Site Request Forgery	Multiple Endpoints	Maloy Roy Orko
CVE-2025-3556	ScriptAndTools	eCommerce-website-in-PHP 3.0	SQL Injection	/product.php	Maloy Roy Orko
CVE-2025-3555	ScriptAndTools	eCommerce-website-in-PHP 3.0	Reflected XSS	/search.php	Maloy Roy Orko
CVE-2025-3537	Tutorials-Website	Employee Management System 1.0	Improper Authorization	/admin/update-user.php	Security Community
CVE-2025-3536	Tutorials-Website	Employee Management System 1.0	Stored XSS	/admin/add-employee.php	Security Community
CVE-2025-3489	Code-Projects	Blood Bank Management System 1.0	SQL Injection	/login.php	Code-Projects Audit
CVE-2025-2041	oretnom23	Vehicle Service Management System 1.0	SQL Injection	/admin/login.php	oretnom23 Audit
CVE-2025-2036	oretnom23	Vehicle Service Management System 1.0	Stored XSS	/admin/mechanics.php	oretnom23 Audit
CVE-2025-2035	oretnom23	Vehicle Service Management System 1.0	Unrestricted File Upload	/admin/update_settings.php	oretnom23 Audit
CVE-2025-1356	needyamin	Online Library Management System 1.0	Broken Authentication	/admin/index.php	needyamin Audit
CVE-2025-1355	needyamin	Online Library Management System 1.0	SQL Injection	/login.php	needyamin Audit
CVE-2025-0844	needyamin	Library Card System 1.0	Stored XSS	/admin/add_card.php	needyamin Audit
CVE-2025-0843	needyamin	Library Card System 1.0	Improper Authorization	/admin/delete_card.php	needyamin Audit
CVE-2025-0842	needyamin	Library Card System 1.0	SQL Injection	/card_details.php	needyamin Audit
CVE-2025-0722	needyamin	Library Card System 1.0	Unrestricted File Upload	/admin/upload_logo.php	needyamin Audit
CVE-2025-0721	needyamin	image_gallery 1.0	Reflected XSS	/view.php (Username)	needyamin Audit
CVE-2024-13205	kurniaramadhan	E-Commerce-PHP 1.0	Stored XSS	/admin/create_product.php	kurniaramadhan Audit
CVE-2024-13204	kurniaramadhan	E-Commerce-PHP 1.0	Broken Authentication	/admin/login.php	kurniaramadhan Audit

Attribution: The matrix distinguishes vulnerabilities attributed to Maloy Roy Orko from records attributed to other researchers, audits, or the wider security community.

### Research Workflow

```text
Reconnaissance
      ↓
Attack Surface Mapping
      ↓
Manual Testing
      ↓
Automated Validation
      ↓
Vulnerability Confirmation
      ↓
Proof of Concept
      ↓
Impact Analysis
      ↓
CWE / CVSS Mapping
      ↓
Technical Documentation
      ↓
Responsible Disclosure
```

---

# 🧰 Security Toolkit

### Web & API Security

`Burp Suite` `OWASP ZAP` `Wapiti` `Nuclei` `ffuf` `Katana` `SQLMap`

### GraphQL Security

`InQL` `GraphQL Voyager` `graphw00f`

### Authentication & Application Security

`JWT Testing` `Browser DevTools` `HTTP Analysis` `Session Testing`

### Network & Infrastructure

`Nmap` `Nessus` `Metasploit`

### Password Security

`Hashcat` `John the Ripper`

---

# 🏴‍☠️ CTF & Competitive Security

* 🏆 **Universal CTF 2026** — Global Rank **47th**
* 🏆 **UIU CTF 2026** — Global Rank **156th / 548 teams**
* 🏆 **Diver OSINT CTF 2026** — Global Rank **218th / 867**
* 🥈 **5th National Research Project Contest 2026** — Runner-Up
* 🏅 **Mebar** — Hall of Fame

---

# 🎓 Education

### East West University

**B.Sc. in Computer Science & Engineering**
2026 – 2030

### Dhaka College

**Higher Secondary Certificate — Science**
2023 – 2025

### Motijheel Government Boys' High School

**Secondary School Certificate — Science**
2013 – 2023

---

# 📜 Certifications & Training

* PEH V1
* Ethical Hacking
* Itronix Cybersecurity Analyst Professional
* Datacom Cybersecurity Job Simulation
* Tata Cyber Security Analyst Job Simulation — Forage

---

# 📈 Currently Learning

```text
API Security
      ↓
Android / Mobile Security
      ↓
Linux Privilege Escalation
      ↓
Windows Privilege Escalation
      ↓
Internal / Network Pentesting
      ↓
Cloud Security
      ↓
Advanced Vulnerability Research
```

---

# 🌐 Online Presence

### 💼 Professional

**LinkedIn**
https://www.linkedin.com/in/maloyroyorko

**GitHub**
https://github.com/Maloyroyorko

### 🛡️ Web Security Insights

**Website:**
https://websecurityinsights.my.id

**Facebook — Web Security Insights By Maloy Roy Orko**
**17K+ followers**
https://www.facebook.com/websecinsights

**YouTube — Web Security Insights By Maloy Roy Orko**
**3.4K+ subscribers · 800K+ website views**
https://www.youtube.com/@MaloyRoyOrko

**Medium — Maloy Roy Orko**
Security research & technical writing
https://medium.com/@maloyroyorko

---

# 📊 Community & Content Reach

| Platform    |                                    Reach |
| ----------- | ---------------------------------------: |
| 🔵 Facebook |                       **17K+ followers** |
| 🔴 YouTube  |                    **3.4K+ subscribers** |
| 🌐 Website  |                          **800K+ views** |
| 📝 Medium   |    Security research & technical writing |
| 💻 GitHub   | Security research & open-source projects |
| 💼 LinkedIn |            Professional security profile |

---

# 🤝 Open to Opportunities

I am interested in opportunities involving:

* Penetration Testing
* Application Security
* API / GraphQL Security
* Vulnerability Research
* Bug Hunting
* Security Research
* Offensive Security
* Cybersecurity Internships

---

# 📫 Contact

📧 **Email:**
[maloyroyorkooo@gmail.com](mailto:maloyroyorkooo@gmail.com)

💼 **LinkedIn:**
https://www.linkedin.com/in/maloyroyorko

💻 **GitHub:**
https://github.com/Maloyroyorko

🌐 **Website:**
https://websecurityinsights.my.id

---

# ⚠️ Responsible Security

All security research and testing presented here is performed for **authorized, educational, research, or responsible-disclosure purposes**.

I do not support unauthorized access, disruption, data theft, or malicious use of security techniques.

---

<p align="center">
  <b>Research • Break • Learn • Secure</b>
</p>
