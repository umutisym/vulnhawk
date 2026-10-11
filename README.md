# 🦅 VulnHawk

> **Focused vulnerability scanner. Zero dependencies. Educational. Bilingual.**
>
> **Hedefli zafiyet tarayıcı. Sıfır bağımlılık. Eğitici. Çift dilli.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Linux-lightgrey)]()
[![Language](https://img.shields.io/badge/Report-TR%20%7C%20EN-orange)]()

---

## 🇬🇧 English

### What is VulnHawk?

VulnHawk is a **focused** vulnerability scanner that finds the **most critical** security issues in a target — not thousands of noise items.

**Philosophy:**
- 🎯 **Focused** — Only 5 critical vulnerability types
- ⚡ **Zero dependencies** — Pure Python stdlib + nmap
- 📖 **Educational** — Every line commented
- 🌍 **Bilingual** — Turkish & English reports
- 📦 **Single file** — `vulnhawk.py` contains everything

### What It Scans

| # | Vulnerability | What It Finds |
|---|---|---|
| 1 | **CVE Matching** | Known vulnerabilities in detected service versions |
| 2 | **Anonymous FTP** | FTP servers with anonymous login enabled |
| 3 | **Open Redis** | Redis databases without authentication |
| 4 | **Telnet Open** | Telnet service (unencrypted, insecure) |
| 5 | **SMB Open** | SMB service (EternalBlue risk) |

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/vulnhawk.git
cd vulnhawk
# No pip install needed!
