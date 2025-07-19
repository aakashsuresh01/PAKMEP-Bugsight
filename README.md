PAKMEP-Bugsight
A powerful reconnaissance automation tool for bug bounty hunters. PAKMEP-Bugsight combines subdomain enumeration, JS scraping, and nuclei scanning in a single bash script.
 🚀 Features

- 🔎 Subdomain Enumeration with `subfinder`
- 🌐 DNS Resolution with `dnsx`
- 🔥 Live Host Detection with `httpx`
- 📦 Port Scanning with `naabu`
- 📁 JS/Config File Scraper using `wget`
- ⚔️ Vulnerability Scanning using `nuclei`
- 📂 Organized Output

---

## 🛠 Installation

### ⚙️ Requirements

Ensure the following tools are installed and added to your `$PATH`:

sudo apt install wget -y(to install golang)

```bash
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install -v github.com/projectdiscovery/dnsx/cmd/dnsx@latest
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
go install -v github.com/projectdiscovery/naabu/v2/cmd/naabu@latest
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest

██████╗  █████╗ ██╗  ██╗███╗   ███╗███████╗██████╗
██╔══██╗██╔══██╗██║ ██╔╝████╗ ████║██╔════╝██╔══██╗
██████╔╝███████║█████╔╝ ██╔████╔██║█████╗  ██████╔╝
██╔═══╝ ██╔══██║██╔═██╗ ██║╚██╔╝██║██╔══╝  ██╔═══╝
██║     ██║  ██║██║  ██╗██║ ╚═╝ ██║███████╗██║    
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═╝    
👁  BugSight by KyberPhilos

🔐 Disclaimer
This tool is for educational and authorized testing only. Misuse of this tool for unauthorized attacks is illegal.
✨ Author
Aakash Suresh
Linkedin:https://www.linkedin.com/in/aakash-suresh-a930aa295/
