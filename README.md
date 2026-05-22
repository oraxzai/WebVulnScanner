# WebVulnScanner PRO 🔥

**Advanced Professional Website Vulnerability Scanner**

A powerful Python-based security tool that performs full website scanning including vulnerability detection, technology fingerprinting, subdomain enumeration, and generates beautiful PDF reports.

![WebVulnScanner](screenshots/cli.png)

### Features
- **Vulnerability Detection**: SQL Injection, XSS, Missing Security Headers
- **Technology Detection**: WordPress, PHP, Apache, Cloudflare, etc.
- **Subdomain Enumeration**: Balanced deep scan
- **WordPress Specific Checks**
- **Professional PDF Reports** with clean design
- **Colorful CLI Interface**

### Screenshots

**1. CLI Interface**
![CLI Interface](screenshots/cli.png)

**2. Professional PDF Report**
![PDF Report](screenshots/report.png)

**3. Testing on DVWA**
![DVWA Testing](screenshots/dvwa.png)

### Technologies Used
- Python 3
- Requests & BeautifulSoup4
- ReportLab (PDF Generation)
- Colorama (CLI Styling)

### How to Install & Run

```bash
git clone https://github.com/oraxzai/WebVulnScanner.git
cd WebVulnScanner

# Install dependencies
pip install -r requirements.txt

# Run the scanner
python scanner.py
