# ATA_honeypot

This is a honeypot project for CMU Course 95-889 final project.  
This honeypot analysis uses the honeypot configuration from https://github.com/mattymcfatty/HoneyPi
  
This configuration alerts on: 
 1. Port Scanning Activities
 2. FTP Connection Attempts
 3. Telnet Connection Attempts
 4. VNC Connection Attempts
 
### Project Scope
Outside of the InfoSec community, there is a lack of awareness, knowledge and concern for cyber threats. The lay person view of security presumes security through obscurity. <br> 
A common thought about security is:
*“Who would want to attack me?!”* <br> 
This project seeks to provide some context to that question.
 
 ### Methodology
**Devices:** <br> 
Raspberry Pi 3B with Buster <br> 
Router, connected via WiFi<br> 
500 MB external hard drive<br> 
32 GB SD card<br> 

**Data Collection**<br> 
Used the standard prompts from HoneyPi to install<br> 
Used journalctl to save and store logs to an external hard drive <br> 
Parsed the logs file using python<br>
<br> 
Collected 2 log files: <br> 
Log File collected from April 7, 2020 - April 14, 2020<br> 
Log File collected from April 23 - April 30, 2020<br> 
Github: https://github.com/normur/ATA_honeypot

