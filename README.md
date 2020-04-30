# ATA_honeypot

This is a honeypot project for CMU Course 95-889 final project.  
This honeypot analysis uses the honeypot configuration from https://github.com/mattymcfatty/HoneyPi
  
This configuration alerts on: 
 1. Port Scanning Activities
 2. FTP Connection Attempts
 3. Telnet Connection Attempts
 4. VNC Connection Attempts
 
### Project Scope
Outside of the InfoSec community, there is a lack of awareness, knowledge and concern for cyber threats. The lay person view of security presumes security through obscurity. 
A common thought about security is:
*“Who would want to attack me?!”* 
This project seeks to provide some context to that question.
 
 ### Methodology
**Devices:** 
Raspberry Pi 3B with Buster 
Router, connected via WiFi
500 MB external hard drive
32 GB SD card

**Data Collection**
Used the standard prompts from HoneyPi to install
Used journalctl to save and store logs to an external hard drive 
Parsed the logs file using python
Collected 2 log files: 
Log File collected from April 7, 2020 - April 14, 2020
Log File collected from April 23 - April 30, 2020
Github: https://github.com/normur/ATA_honeypot

