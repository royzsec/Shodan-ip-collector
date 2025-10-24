README.md
markdown Copy# Shodan IP Collector

A **Bash script with a text-based UI** to collect IP addresses from Shodan using custom dorks. The script stores your Shodan API key for future use and supports real-time progress updates.

---

## Features
- **Interactive UI:** Easy-to-use menu system.
- **API Key Storage:** Save your Shodan API key securely.
- **Real-Time Progress:** Track IP collection with a progress bar.
- **Flexible Dorks:** Supports any Shodan search query.

---

## Requirements
- `dialog` (for the UI)
- `jq` (for JSON parsing)
- `curl` (for API requests)
- A **Shodan API key** ([Get one here](https://www.shodan.io/))

---

## Installation

### 1. Clone the Repository
```bash
git clone git@github.com\:royzsec/Shodan-ip-collector.git
cd Shodan-ip-collector
2. Make the Script Executable
bash Copychmod +x shodan_ui.sh
3. Install Dependencies
Ubuntu/Debian:
bash Copysudo apt update
sudo apt install dialog jq curl
macOS:
bash Copybrew install dialog jq curl

Usage
1. Run the Script
bash Copy./shodan_ui.sh
2. Follow the Prompts

Enter your Shodan API key (saved for future use).
Enter your Shodan dork (e.g., hostname:.gov.uk port:21).
The script will collect IPs and save them to a file (shodan_ips_[timestamp].txt).


Example Dorks

apache port:80
hostname:.gov.uk
product:nginx country:US


Troubleshooting

Permission Denied: Ensure the script is executable (chmod +x shodan_ui.sh).
Missing Dependencies: Install dialog, jq, and curl as shown above.
API Errors: Double-check your Shodan API key.


License
This project is open-source and available under the MIT License.
 Copy---

### **How to Use This README**
1. Save this content as `README.md` in your project directory.
2. Push it to GitHub:
   ```bash
   git add README.md
   git commit -m "Add README"
   git push origin main
