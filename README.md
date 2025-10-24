# Shodan IP Collector

A user-friendly Bash tool with a text-based UI for fetching IPs from Shodan using custom dorks. Store your API key once, enter any dork, and get IPs saved to a file with real-time progress updates. Ideal for security research and penetration testing.

## Requirements
- dialog
- jq
- curl
- Shodan API key

---

## Installation & Setup

1. Clone the repository:
git clone git@github.com:royzsec/Shodan-ip-collector.git

2. Make the script executable:
cd Shodan-ip-collector
chmod +x shodan-dork


 Copy2. First run:
 ./shodan_ui.sh
- Enter your Shodan API key (it will be saved for future use)
- Enter your search dork when prompted

3. Results will be saved to a file named `shodan_ips_[timestamp].txt`

---

## Example Dorks

Here are some example dorks you can try:
hostname:.gov.uk port:21
apache country:US
product:nginx os:linux
title:"webcam" city:NewYork
org:amazon port:80


---

## Features

- Interactive menu system
- Secure API key storage for future sessions
- Real-time progress tracking during IP collection
- Flexible search queries
- Automatic result saving with timestamp

---

## Troubleshooting

| Issue                | Solution                                  |
|----------------------|-------------------------------------------|
| Permission denied    | Run `chmod +x shodan-dork`               |
| Missing dependencies | Install dialog, jq, and curl              |
| API errors           | Verify your Shodan API key                |
| Connection issues    | Check your internet connection            |

---

## License

This project is open-source under the MIT License.

© 2025 royzsec








 
