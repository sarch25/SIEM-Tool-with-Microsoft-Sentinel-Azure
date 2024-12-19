<h1>SIEM Tool with Microsoft Sentinel Azure</h1>

## Summary


Developed a SIEM tool for a home lab by utilizing Azure services. By utilizing Azure's cloud platform, I created a virtual environment for testing purposes. Specifically, I configured a honeypot virtual machine (VM) with purposefully disabled firewalls to mimic actual attack scenarios. 

A key component of the project was setting up an Azure workspace for Log Analytics, which acted as a repository for gathering and processing logs from the virtual machine used as a honeypot. By improving situational awareness and proactive threat identification, integration with Microsoft's cloud SIEM solution, Azure Sentinel, it provided real-time visibility into global login attempts on a dynamic global map. 

Additionally, I retrieved unsuccessful login data from Windows Security Event Logs using PowerShell scripts for automation, and I used a third-party IPGeolocation API to enhance it with geographic information. By streamlining the analysis process, this automation enhanced incident response capabilities.

![Screenshot 2024-03-09 210946](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/609f79f5-61b1-4f1b-9be7-88014d7378cf)
#
### Skills Learned


- Setting up and configuring Azure services for cybersecurity experimentation
- Designing and implementing a honeypot VM to simulate real-world attack scenarios
- Utilizing Log Analytics and Azure Sentinel for log collection, analysis, and threat detection
- Developing and implementing PowerShell scripts for automation and data enrichment
- Continuous refinement and enhancement of SIEM tool functionality for improved incident response capabilities

### Tools Used


- Azure Sentinel for SIEM capabilities
- Virtual machines (VMs) for experimentation
- Log Analytics workspace for log collection and analysis
- PowerShell scripting for automation
- IP Geolocation API for enriching data with geographic information

## Images

#### Created a honeypot in Azure, deploying a virtual machine with intentional vulnerabilities to attract and analyze potential cyberattacks.

![Screenshot 2024-03-09 115549](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/52b26df5-e1c4-45b0-8def-6e821db9cde0)
#

#### Adjusted Windows Defender Firewall settings to intentionally disable protections, leaving my virtual machine exposed to potential attacks from any global source.

![Screenshot 2024-03-09 111204](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/c43384ce-5c87-447c-9faa-bfa17b35e1a1)
#

#### Configured Azure Log Analytics to collect data from the virtual machine by linking it to a Log Analytics workspace. Set up data collection rules to gather system logs, performance metrics, and security events, enabling centralized monitoring and integration with Azure Sentinel for threat analysis.
![Screenshot 2024-03-09 120220](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/aa658682-8c53-4e33-8252-433240ab945d)
![Screenshot 2024-03-09 154232](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/1457cf8c-0c76-4712-a15b-3ea852dd76bd)
#

#### Used a PowerShell script to collect failed login attempts to the honeypot, capturing the username, password, and timestamp. Also, integrated the IPGeolocation API within the script to gather geographic information from attacker.
![Screenshot 2024-03-09 110905](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/ddeeae1f-e7df-417d-9bb1-84b2c68c05bc)
#

#### This dynamic map visualizes real-time login attempts across the globe. Each attack is geolocated using IPGeolocation, with a counter tracking and displaying the number of attacks over time.
![Screenshot 2024-03-09 210946](https://github.com/sarch25/SIEM-Tool-with-Microsoft-Sentinel-Azure/assets/130470960/609f79f5-61b1-4f1b-9be7-88014d7378cf)
#
