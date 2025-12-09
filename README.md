🔵 Blue Team Labs
Real Logs / SOC investigation / simulated threats

This repository contains a collection of hands-on labs designed to train learning skills.:

Log analysis

Anomaly detection

SOC Tier 1 / Tier 2 research

Threat Hunting reasoning

Incident response

All labs use simulated real data, covering common security scenarios.

🎯 Targets

✔ Train investigation in Linux, DNS and Windows logs
✔ Create behavior-based detection reasoning
✔ Simulate real incidents (brute force, exfiltration, persistence)
✔ Develop SOC maturity chosen by recruiters
✔ Serves as a professional technical portfolio

📁 Repository structure
blue-team-labs/
│
├── logs/
│ ├ ─ ─ linux_auth.log
│ ├ ─ ─ DNS.log
│ └ ─ ─ windows.json
│
├── labs/
 brut── brute_force/
│ ├ ─ ─ challenge.md
│ └ ─ ─ hints.txt
│
└── answers/
    └── brute_force.md

🧪 Content of Labs
1. Brute Force-Linux Auth Logs

In this challenge, the analyst must identify:

Repeated login attempts

Suspected IPs

Target accounts

Brute force indicators

Anomalous patterns

The answers/brute_force. md file provides a technical explanation of how the investigation should be done.

2. DNS Logs

Ideal exercise for training:

Rare domains

Suspicious queries

Anomalous Volume

Possible tunneling attempts

3. Windows Logs

Base Dataset for future analysis, including:

Suspicious executions

Unusual processes

Critical events

▶️ How To Use

Open the log files, analyze the events and try to identify:

✔ Anomalies
✔ Attack indicators
✔ Behavior patterns
✔ Possible TTPs

Then compare with the answer in / answers/.

Demonst️ Demonstrated skills with this repository

SOC investigation

Threat Hunting in logs

Analysis of Linux Auth, DNS and Windows

Behavioral detection

Technical documentation and methodologies Blue Team

MITRE ATT&CK

📬 Contact

Gustavo Okamoto
Cybersecurity Analyst – SOC / Threat Detection
📧 gugaokamoto1@gmail.com

🔗 linkedin.com/in/gustavo-okamoto-de-carvalho-ti
🔗 github.com/gustavo89587
