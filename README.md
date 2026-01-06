Elastic SIEM Home Lab Project

This project demonstrates my ability to deploy, configure, and operationalize an Elastic SIEM environment using:

- Elasticsearch

- Kibana

- Fleet Server

- Elastic Agent

- Linux Endpoint with Elastic Defend
  
- Kibana

- Fleet Server

- Elastic Agent

- Linux Endpoint with Elastic Defend

- SIEM detection rules & alerting

  Purpose of the project:

1. Build a functional detection pipeline

2. Collect security telemetry from a Linux host

3. Deploy Elastic Defend

4. Trigger & analyze real alerts

5. Visualize logs and detections in Kibana

6. Build a functional detection pipeline

7. Collect security telemetry from a Linux host

8. Deploy Elastic Defend

9. Trigger & analyze real alerts

10. Visualize logs and detections in Kibana

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

1. Set up Docker-based ELK stack

2. Configure Fleet Server + policies

3. Install Elastic Agent on Linux host

4. Enable Elastic Defend integration

5. Turn on over 1,200 SIEM rules

6. Trigger test alerts (systemctl event, custom rule)

7. Validate logs via Discover

8. View alerts via Security → Alerts

Screenshots
✔️ Fleet Agents – Both Healthy
<img width="1248" height="681" alt="Screenshot from 2026-01-06 15-28-15" src="https://github.com/user-attachments/assets/5863090f-d871-439e-b320-c3cd9df29d47" />

✔️ SIEM Alerts – Working Alerts Triggered
<img width="2493" height="939" alt="Screenshot from 2026-01-06 15-29-57" src="https://github.com/user-attachments/assets/aa7cfde7-9bd0-4c7b-8dc5-01cf9c30e88b" />

✔️ Detection Rules – Enabled
<img width="2489" height="1233" alt="Screenshot from 2026-01-06 15-31-53" src="https://github.com/user-attachments/assets/273a00d3-55c1-4298-91a0-83f3986df79c" />

✔️ Discover View – Logs Flowing
<img width="2494" height="1293" alt="Screenshot from 2026-01-06 16-11-14" src="https://github.com/user-attachments/assets/10564d4b-c359-408a-bdf9-0694086153c9" />

✔️ Docker Status + Agent Status
<img width="1224" height="482" alt="Screenshot from 2026-01-06 16-08-23" src="https://github.com/user-attachments/assets/339c2575-5254-427c-bc99-81b6fe9a1036" />


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

1. SIEM deployment & administration

2. Linux endpoint security

3. Docker orchestration

4. Event log analysis

5. Rule tuning

6. Security monitoring foundations

7. Troubleshooting Fleet/Agent connectivity

8. Linux endpoint security

9. Docker orchestration

10. Event log analysis

11. Rule tuning

12. Security monitoring foundations

13. Troubleshooting Fleet/Agent connectivity


