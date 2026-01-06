Elastic SIEM Home Lab Project
🔍 Overview

This project demonstrates my ability to deploy, configure, and operationalize an Elastic SIEM environment using:

Elasticsearch

Kibana

Fleet Server

Elastic Agent

Linux Endpoint with Elastic Defend

SIEM detection rules & alerting

Purpose of the project:

Build a functional detection pipeline

Collect security telemetry from a Linux host

Deploy Elastic Defend

Trigger & analyze real alerts

Visualize logs and detections in Kibana

[Linux Host] → Elastic Agent → Fleet Server → Elasticsearch → SIEM Alerts (Kibana)


| Component            | Purpose                          |
| -------------------- | -------------------------------- |
| **Elasticsearch**    | Stores logs + alert data         |
| **Kibana**           | Visualization + SIEM             |
| **Fleet Server**     | Manages agents / policies        |
| **Elastic Agent**    | Endpoint collection & protection |
| **Elastic Defend**   | EDR-style endpoint security      |
| **Docker / Compose** | Runs the ELK stack               |


 Deployment Steps (Summary)

Set up Docker-based ELK stack

Configure Fleet Server + policies

Install Elastic Agent on Linux host

Enable Elastic Defend integration

Turn on over 1,200 SIEM rules

Trigger test alerts (systemctl event, custom rule)

Validate logs via Discover

View alerts via Security → Alerts

Screenshots
✔️ Fleet Agents – Both Healthy
</home/adminn/Pictures/Screenshots/Screenshot from 2026-01-06 15-28-15.png>
✔️ SIEM Alerts – Working Alerts Triggered
</home/adminn/Pictures/Screenshots/Screenshot from 2026-01-06 15-29-57.png>
✔️ Detection Rules – Enabled
</home/adminn/Pictures/Screenshots/Screenshot from 2026-01-06 15-31-53.png>
✔️ Discover View – Logs Flowing
</home/adminn/Pictures/Screenshots/Screenshot from 2026-01-06 16-11-14.png>
✔️ Docker Status + Agent Status
</home/adminn/Pictures/Screenshots/Screenshot from 2026-01-06 16-08-23.png>


Alerts Generated

During testing, I successfully triggered:

Elastic Agent Service Termination Alert

Custom rule event alert

Additional system-level events

These confirmed that:
✔️ Logs were flowing
✔️ Rules were enabled
✔️ Alerts were firing
✔️ Endpoint was communicating with Fleet

 Skills Demonstrated

SIEM deployment & administration

Linux endpoint security

Docker orchestration

Event log analysis

Rule tuning

Security monitoring foundations

Troubleshooting Fleet/Agent connectivity

 Conclusion

This project shows practical experience building and running a real SIEM pipeline using Elastic, end-to-end.


