#Shodan IP Collector
#A Bash Script for Shodan IP Collection
#Installation & Setup
bash Copygit clone git@github.com:royzsec/Shodan-ip-collector.git
cd Shodan-ip-collector
chmod +x shodan_ui.sh
sudo apt update && sudo apt install dialog jq curl  # For Debian/Ubuntu
brew install dialog jq curl                         # For macOS
Usage Instructions
Run the application:
bash Copy./shodan_ui.sh

#First run: Enter your Shodan API key (saved for future use)
Enter your search dork when prompted
Results saved to shodan_ips_[timestamp].txt

#Example Dorks
 Copyhostname:.gov.uk port:21
apache country:US
product:nginx os:linux
title:"webcam" city:NewYork
org:amazon port:80
#Features
• Interactive menu system
• Secure API key storage
• Real-time progress tracking
• Flexible search queries
• Automatic result saving
#Troubleshooting
IssueSolutionPermission deniedRun chmod +x shodan_ui.shMissing dependenciesInstall dialog, jq, curlAPI errorsVerify your Shodan API keyConnection issuesCheck internet connection

#License
Open-source under MIT License
© 2025 royzsec
