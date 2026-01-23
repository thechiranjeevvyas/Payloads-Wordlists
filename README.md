# 🧰 Payload & Wordlists

  <p align="center">
    <b>A curated, practical collection of offensive security payloads and wordlists for real-world testing.</b><br/>
    Designed for penetration testers, bug bounty hunters, and security learners.
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Focus-Offensive%20Security-red?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Use-Educational%20%26%20Authorized%20Testing-blue?style=for-the-badge"/>
  </p>

---

## 📌 About This Repository

**Payload & Wordlists** is a structured GitHub repository containing:

- Handpicked **XSS** and **SQL Injection** payloads
- Ready-to-use **username wordlists**
- Clean folder hierarchy for fast integration with tools
- Payloads tested and refined for **real-world scenarios**

This repository follows a simple philosophy:

> _Old-school payloads still work — if you know when and how to use them._

---

## 🗂️ Repository Structure

```text
Payload-&-Wordlists/
│
├── payloads/
│   ├── xss/
│   │   └── xss-payloads.txt
│   │
│   └── sqli/
│       └── sqli-payloads.txt
│
├── usernames/
│   └── usernames.txt
│
└── README.md
```

## 🧪 Payload Categories

### 🔴 XSS Payloads

- Reflected XSS
- Stored XSS
- DOM-based XSS
- Filter bypass payloads
- Context-aware injections (HTML, JS, attributes)

📂 **Location**

/payloads/xss/

---

### 🔵 SQL Injection Payloads

- Error-based SQLi
- Boolean-based SQLi
- Time-based blind SQLi
- Authentication bypass payloads
- WAF-aware payload variations

📂 **Location**

/payloads/sqli/

👤 Username Wordlists

Common usernames

Admin & service accounts

Login brute-force ready

Useful for labs, CTFs, and real assessments

📂 Location

/usernames/usernames.txt

🛠️ Commonly Used Tools (Quick Access)

  <p align="center"> <a href="https://portswigger.net/burp"> <img src="https://img.shields.io/badge/Burp%20Suite-orange?style=for-the-badge&logo=burpsuite&logoColor=white"/> </a> <a href="https://sqlmap.org/"> <img src="https://img.shields.io/badge/sqlmap-red?style=for-the-badge&logo=python&logoColor=white"/> </a> <a href="https://cirt.net/Nikto2"> <img src="https://img.shields.io/badge/Nikto-black?style=for-the-badge&logo=linux&logoColor=white"/> </a> <a href="https://www.metasploit.com/"> <img src="https://img.shields.io/badge/Metasploit-blue?style=for-the-badge&logo=metasploit&logoColor=white"/> </a> </p>
  ⚙️ Usage Examples
  Using payloads with sqlmap
  sqlmap -u "http://target.com/page?id=1" --batch --risk=3 --level=5

Testing XSS manually

  <script>alert(1)</script>

Brute-force usernames
hydra -L usernames/usernames.txt -P passwords.txt target ssh

⚠️ Disclaimer

This repository is strictly for educational purposes and authorized security testing only.

Do NOT use these payloads on systems without explicit permission

The author is not responsible for misuse or illegal activities

Always follow responsible disclosure and ethical hacking practices.

🤝 Contributions

Contributions are welcome and encouraged.

You can:

Add new payloads

Improve existing bypass techniques

Submit optimized wordlists

Fix formatting or documentation issues

📌 Please ensure payloads are clean, categorized, and tested before submitting a pull request.

⭐ Support

If you find this repository useful:

⭐ Star the repository

🍴 Fork it

🧠 Learn from it

🔐 Hack responsibly
