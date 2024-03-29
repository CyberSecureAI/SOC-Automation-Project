**Welcome to the SOC Automation Project.**

<h2>Objective</h2>

The objective is to build a comprehensive **S**ecurity **O**rchestration, **A**utomation, and **R**esponse (SOAR) solution, starting from scratch and incorporating Wazuh and TheHive for effective case management. The possibilities for automation are limitless, and your creativity is the key to unlocking its full potential.

<h2>Prerequisite</h2>

- How to set up a virtualbox (Win10) _**[link repo: How to setup a homelab]**_
- How to set up a cloud server via DigitalOcean (2x Ubuntu 22.04) _**[link repo: how to spin up a cloud server]**_

Use the link: https://m.do.co/c/7c4cda4fcca2 <- To get a free $200 credit for the first 60 days with Digital Ocean

<h2>Apps Installed</h2> 

- Sysmon - Windows system monitoring tool designed to track and log detailed information about system activity, providing insights for threat detection and forensic analysis.
- Wazuh - Open source cybersecurity platform that integrates SIEM and XDR capabilities
- TheHive - 4-in-1 security incident response platform



<h2>Project Outline</h2>

Phase 1 -  Design
1. Drafting a visual representation: Develop a diagram that outlines the logical construction of our lab environment.
2. Mapping the flow: Illustrate the anticipated data flow to provide a clear visual representation.
3. Component visualization: Use the diagram to visually identify all the necessary components required for seamless functionality.
4. Practicality assessment: Evaluate the practical aspects of the constructed lab by visually inspecting the diagram.

**_Having the ability to draw a basic and secure lab diagram using the draw.io tool can be advantageous during interviews where such visual representations may be requested.._**

Phase 2 - Install
- Deploying Components and Configuring Cloud Environments
  - Installing Windows 10 within VirtualBox
  - Implementing Sysmon on the Windows 10 operating system
  - Setting up two Ubuntu servers:
    - One dedicated to hosting the Wazuh application
    - Another designated for hosting TheHive application 

Phase 3 - Configuration
-  Configure endpoints + servers to communicate to each other

Phase 4 - Telemetry
-   Generate telemetry related to mimikatz on our endpoint which will trigger an alert on Wazuh

Phase 5 - SOAR
-   How to setup SOAR and integrate everything together

**[Hive Notes]**
- We send alerts to the hive to keep track on who's working on the alerts

[Terms]
- IOCS: Indicators of Compromise

Mimikatz https://github.com/gentilkiwi/mimikatz/releases/tag/2.2.0-20220919
