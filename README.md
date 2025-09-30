# SIEM-Lab-Project
Hands-on SIEM project using Elasticsearch, Kibana, and Winlogbeat. Configured log collection from Windows VM, built dashboards for login activity, and analysed security events.

This project demonstrates the setup and use of a Security Information and Event Management (SIEM) system in a virtualized lab environment.
It was designed to replicate real-world SOC workflows, including log collection, event monitoring, and dashboarding for threat detection.

🔹 Objectives

Install and configure Elasticsearch & Kibana on Ubuntu VM.

Configure Winlogbeat on a Windows VM to forward security event logs.

Collect and visualise logs for user logins, failed logins, and PowerShell activity.

Build Kibana dashboards to detect suspicious activity and monitor authentication trends.

🔹 Key Features

Data Ingestion: Windows Event Logs (4624 – Successful Logon, 4625 – Failed Logon).

Dashboards:

Login trends over time (successful vs failed).

Top usernames from failed logins.

Failed logins by source IP.

Use Case: Identify brute-force attempts, monitor user behavior, and improve visibility into endpoint activity.

🔹 Tools & Technologies

Elasticsearch – log storage and indexing.

Kibana – data visualization and dashboards.

Winlogbeat – log forwarder from Windows Event Viewer.

VirtualBox – lab virtualization.

🔹 Results

Successfully built a working SIEM pipeline.

Detected and visualized successful vs failed logins.

Created actionable dashboards for SOC-style monitoring.

📷 Screenshots included in the screenshots/ folder.
