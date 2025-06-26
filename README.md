# VulnScanPy 🔍

A lightweight Python-based web application vulnerability scanner that detects **SQL Injection** and **Cross-Site Scripting (XSS)** vulnerabilities. Automatically crawls the target site, tests forms and URLs, and generates a readable vulnerability report.

---

## 🚀 Features

- ✅ Crawls internal links of the target domain
- 🧪 Tests for **SQL Injection** via GET & POST
- 🧪 Tests for **XSS** via GET & form injection
- 📝 Generates a vulnerability report (`.txt`) with payload details
- 🔓 Works on public test sites and local environments

---

## ⚙️ Requirements

- Python 3.x
- Required libraries:
  ```bash
  pip install requests beautifulsoup4
  
Usage

The scanner will:

Crawl all reachable pages

Scan for SQLi and XSS

Save results to vulnerability_report.txt
