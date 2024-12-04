# centralized-GitHub-repository-
Project Overview:
This project automates task to monitor the systems performance, security, and incase of a security breach it will send out alerts. It includes log files to identify suspicious activity (unauthorized access), and will later create a new file and makes it into a report. It also monitors CPU and Memory usage, these performance metrics help send out alerts if they are higher than the specified thresholds which in this case is 90. For the security part, it uses Nmap to detect vulnerabilities in the network and with the help of Scapy it also captures and monitors network traffic (IP addresses). 

Installation: 
To ensure that this project works successfully, you must first ensure that all files are in the same directory or folder in order for the code to execute. Then you would want to install Nmap from Nmap.org (we personally recommended) or within your terminal. Next would be installing Scapy, which could be downloaded by 'pip installing scapy'. But, while installing scapy, it also a good idea to install Psutil which helps monitor performance, this can be done by pip installing it, 'pip install psutil'. For the email alerts part, first you have to enable 2FA (2-step verification) on your Gmail account. After you've done that, an option to create an "app-specific password" is available, update the email in your script with your credentials (email and app-specific password) and you will be all setup!

Usage:
In order for this script to run and analyze the data, you must first put the "system_log.log" file in the script's directory and run the script so it could create a "summary_report.txt" which flags suspicious entries. System performance records such as CPU and memory usage are logged in real time in "performance_log.txt" and will create an alert if the CPU usage exceeds the specified threshold. Nmap scans for open ports and services which trys to find potential vulnerabilities. Packet sniffing identify destinations IP using both IP and TCP layers to monitor the suspicious activity.


Team Members:

Project Manager: 
Alexander Lee

Systems Modelers:
Susy Hernandez-Reyes 
Raymond Lee

Python Developers:
Ryan Rasool
Ebby Bejoy

Data Analysts:
Mahsa Zarabi
Alicia Pongpunwattana
