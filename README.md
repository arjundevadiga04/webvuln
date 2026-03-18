# 🌐 Web Vulnerability Scanner

**Author:** Arjun  
**Description:** A simple Python-based toolkit to demonstrate basic web vulnerability checks (SQL Injection and XSS).  

---

## ✨ Features
- **SQL Injection Check**: Sends a test payload (`' OR '1'='1`) to a query parameter and inspects the response for error messages.
- **XSS Check**: Injects a JavaScript payload (`<script>alert('XSS')</script>`) and verifies if it appears in the response.
- Logging for clear, structured output.
- Lightweight and easy to extend.

---

## 📦 Requirements
- Python 3.x
- [Requests](https://docs.python-requests.org/en/latest/)
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/)

Install dependencies:
```bash
pip install requests beautifulsoup4
🚀 Usage
Run the script:
python3 webvulnscanner.py


You’ll be prompted to enter a target URL:
Enter target URL: http://example.com/page


🔍 SQL Injection Test
INFO: No SQL Injection signs.
WARNING: Possible SQL Injection vulnerability detected.


XSS Test
INFO: No XSS signs.
WARNING: Possible XSS vulnerability detected.



⚠️ Notes
- This tool is for educational and demonstration purposes only.
- Do not use against systems without explicit permission — unauthorized testing is illegal.
- The payloads used are basic examples and not comprehensive vulnerability checks.

🛠 Example Workflow
- Run the script.
- Enter a target URL (e.g., http://testphp.vulnweb.com/listproducts.php).
- Observe results for SQL Injection and XSS checks.




