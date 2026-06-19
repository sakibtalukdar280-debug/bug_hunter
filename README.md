# 🐛 Bug Hunter Swiss Knife v4.0

![Version](https://img.shields.io/badge/version-4.0-blue)
![Modules](https://img.shields.io/badge/modules-31-green)
![Python](https://img.shields.io/badge/python-3.8+-yellow)
![License](https://img.shields.io/badge/license-MIT-red)

**Professional Bug Bounty Toolkit | 31 Modules | All-in-One**

---

## 📸 Preview

```

╔══════════════════════════════════════════════════════╗
║     🐛  BUG HUNTER SWISS KNIFE v4.0  🐛            ║
║        Professional Bug Bounty Toolkit            ║
║             31 Modules | All-in-One              ║
╚══════════════════════════════════════════════════════╝

```

---

## 🚀 Features

### Core Modules (1-10)
| # | Module | Description |
|---|--------|-------------|
| 1 | Web Crawler | Find endpoints, links, parameters |
| 2 | Vulnerability Scanner | XSS, SQLi, Open Redirect |
| 3 | Port Scanner | Multi-threaded scanning |
| 4 | Technology Detector | 50+ technologies |
| 5 | Sensitive File Finder | .env, .git, backups |
| 6 | Directory Bruteforcer | Hidden directories |
| 7 | WAF Detector | 15+ WAF signatures |
| 8 | Full Audit | Automated all-in-one scan |
| 9 | Report Generator | HTML reports |
| 10 | Auth Handler | Auto cookie extraction |

### Extended Modules (11-20)
| # | Module | Description |
|---|--------|-------------|
| 11 | Subdomain Finder | 100+ subdomains |
| 12 | Header Analyzer | Security headers audit |
| 13 | JS Secret Finder | API keys, tokens |
| 14 | Wayback Machine | Historical URLs |
| 15 | Email Harvester | Extract emails |
| 16 | WordPress Scanner | Version, users |
| 17 | Sitemap Parser | URL extraction |
| 18 | CORS Scanner | Misconfiguration test |
| 19 | Screenshot Capture | Page screenshots |
| 20 | Link Checker | Broken links |

### Advanced Modules (21-28)
| # | Module | Description |
|---|--------|-------------|
| 21 | Security Headers | CSP, HSTS, X-Frame |
| 22 | Directory Listing | Exposed directories |
| 23 | Open Redirect | Redirect vulns |
| 24 | Subdomain Takeover | Dangling DNS |
| 25 | API Discovery | REST, GraphQL |
| 26 | SSRF Checker | Server-side forgery |
| 27 | IDOR Detection | Direct object reference |
| 28 | Rate Limit Check | Brute force test |

### Tools (29-31)
| # | Module | Description |
|---|--------|-------------|
| 29 | Multi-Target Scanner | Bulk scanning |
| 30 | Discord Webhook | Notifications |
| 31 | Pro Report | Charts & graphs |

---

## 📦 Installation

### One Command (Termux/Linux)
```bash
apt update
apt full-upgrade -y
pkg install git zip unzip python -y

git clone https://github.com/sakibtalukdar280-debug/bug_hunter.git

cd bug_hunter

ls

unzip bug_hunter.zip

ls

cd bug_hunter

pip install -r requirements.txt

bash setup.sh

python bug_hunter_menu.py
```

Manual

```bash
git clone https://github.com/sakibtalukdar280-debug/bug_hunter.git
cd bug_hunter
pip install -r requirements.txt
python bug_hunter_menu.py
```

---

🎯 Usage

```bash
# Interactive Menu
python bug_hunter_menu.py

# CLI Mode
python bug_hunter.py --crawl https://example.com
python bug_hunter.py --scan https://example.com/page?id=1 --test xss
python bug_hunter.py --full https://example.com --report report.html
python bug_hunter.py --crawl https://example.com --cookies "session=abc"
```

---

⚠️ Disclaimer

For authorized testing only!

· Only use on systems you own or have permission
· Not responsible for misuse
· Follow responsible disclosure

---

👤 Author

Sakib Talukdar

· GitHub: @sakibtalukdar280-debug

---

📄 License

MIT License

---

Made with ❤️ in Bangladesh 🇧🇩
