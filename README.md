# Cloud-Deployed-T-Pot-Honeypot-Threat-Monitoring-Analysis
Deployed a cloud-based T-Pot honeypot to observe and document real-world attack attempts. Captured unauthorized access attempts and analyzed common attack patterns against exposed services.

# Overview

This project documents the deployment of a public-facing T-Pot multi-honeypot platform in a cloud environment to capture and analyze real-world malicious traffic.

The goal was to simulate an exposed internet host, observe attacker behavior, and analyze common threat patterns such as brute-force attempts and automated scanning.


# Objectives

- Deploy T-Pot on a cloud VPS

- Expose the server to the internet

- Capture real attack attempts

- Analyze basic attacker behavior


# Tools & Technologies

- T-Pot (Multi-honeypot platform)

- Ubuntu Linux (Cloud VPS)

- HTTPS Web Dashboard

- SSH

# Key Findings

Public IP addresses are scanned shortly after being exposed

SSH is one of the most targeted services

Most attack attempts appear automated

Basic usernames like root and admin are commonly used in attacks





<img width="800" height="419" alt="honeypot2" src="https://github.com/user-attachments/assets/07a55ef0-f657-4998-8a7a-e0ec4c861359" />

- *Deployed Ubuntu 22.04 (4GB) cloud instance in Chicago to host a T-Pot honeypot with a public IP for real-world attack monitoring.*

  <p align="center">

</p>

<br>

<p align="center">

</p>


### Firewall Configuration

<img width="800" height="858" alt="image" src="https://github.com/user-attachments/assets/4cde1114-bf82-4933-bde6-67dbbe25d964" />

- *Configured firewall rules to balance attack surface exposure for threat monitoring while maintaining secure administrative access.*

</p>

<br>

<p align="center">

</p>

<img width="800" height="438" alt="honeypot3" src="https://github.com/user-attachments/assets/dcd60884-8485-47ff-baa4-9f8b607d2723" />

- *T-Pot Dashboard displaying real-time attack monitoring and integrated threat analysis tools.*

</p>

<br>

<p align="center">

</p>

<img width="800" height="648" alt="image" src="https://github.com/user-attachments/assets/66bd7e6e-fd6d-4b76-b5ad-3ca66c646838" />

- *Overview of the honeypot’s public IP showing total attacks, number of different attackers, and the most targeted services such as SSH and MySQL.*

  

