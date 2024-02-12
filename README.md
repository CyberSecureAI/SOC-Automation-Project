**Welcome to the SOC Automation Project.**

[Objective]
The goal here is to start from nothing to a fully integrated SOAR solution incorporating Wazuh & TheHive for case management. 
The sky is the limit when it comes to automation and it is up to your creativity.

[Prerequisite]
- How to set up a virtualbox (Win10) [link repo: How to setup a homelab]
- How to set up a cloud server via DigitalOcean (2x Ubuntu 22.04) [link repo: how to spin up a cloud server]

Use the link: https://m.do.co/c/7c4cda4fcca2 <- To get a free $200 credit for the first 60 days with Digital Ocean

[Apps Installed]
- Sysmon
- Wazuh - Open source cybersecurity platform that integrates SIEM and XDR capabilities
- TheHive - 4-in-1 security incident response platform



[Summary]
- Phase 1: Design
-   Creating a diagram & mapping out how we would like to build out our lab - logically
-   This will allow us to visually see how the data might flow while visually seeing all the pieces that is required to make this all work
-   Some interviews will request you to draw a diagram of a basic lab and secure it
-   Using draw.io tool (free)
- Phase 2: Install
-   installing the components and setting up in the cloud
- Phase 3: Configuration
-  Configure endpoints + servers to communicate to each other
- Phase 4: Telemetry
-   Generate telemetry related to mimikatz on our endpoint which will trigger an alert on Wazuh
- Phase 5: SOAR
-   How to setup SOAR and integrate everything together

[Hive Notes]
- We send alerts to the hive to keep track on who's working on the alerts

[Terms]
- IOCS: Indicators of Compromise

Mimikatz https://github.com/gentilkiwi/mimikatz/releases/tag/2.2.0-20220919
