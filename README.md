🛡️ Blue Team Labs — Detection & Incident Response
Hands-on Blue Team labs focused on detection engineering, incident response, and SOC operations.
This repository contains practical security labs that simulate real-world attacks and defensive workflows used by modern SOC and DFIR teams.

🎯 Objective
The goal of these labs is to demonstrate how defenders think and act, not just tools or theory.
Each lab focuses on:
Understanding attacker behavior
Detecting suspicious activity
Investigating incidents
Responding with structured methodology
🔍 What You’ll Find Here
✔ Detection engineering scenarios
✔ Incident response simulations
✔ Alert triage & investigation logic
✔ Log analysis & correlation
✔ Blue Team mindset in practice
🧠 Blue Team Focus Areas

Threat Detection
Incident Response (IR)
Log Analysis & Correlation
Endpoint & Network Visibility
SOC Analyst workflows
MITRE ATT&CK mapping

🧪 Example Lab Scenarios
Suspicious process execution on endpoints
Malware execution and behavior analysis
Lateral movement indicators
Persistence mechanisms
Alert validation and false positive analysis
Each scenario is designed to answer:
“What would a SOC analyst do next?”

🧩 Methodology Used
Copiar código
Text
Alert / Suspicious Activity
        ↓
Validation & Context
        ↓
Log & Event Correlation
        ↓
Threat Assessment
        ↓
Containment & Response
        ↓
Lessons Learned
🛠️ Tools & Concepts Applied
SIEM fundamentals (Elastic / Sentinel / Wazuh-like logic)
Endpoint telemetry
Windows Event IDs
Linux logs
Process & network analysis
MITRE ATT&CK techniques
Detection logic design

📂 Repository Structure
blue-team-labs/
├── detection/
│   ├── process-analysis.md
│   ├── persistence-detection.md
├── incident-response/
│   ├── triage.md
│   ├── containment.md
│   └── lessons-learned.md
├── logs/
│   └── sample-events.json
└── README.md

🧠 Why This Matters
Blue Team is not about running tools — it’s about:
Thinking like an attacker
Detecting early signals
Making fast, informed decisions
Reducing impact
This repository reflects how real SOC teams operate, not CTF-style labs.

🧪 Lab Context
These labs are part of Okamoto Security Labs, where I simulate:
SOC environments
Incident response workflows
Detection logic
Threat hunting techniques
Analyst decision-making under pressure

🎯 Target Audience
SOC Analysts (Tier 1–2)
Threat Hunters
Detection Engineers
DFIR Analysts
Blue Team Engineers

📌 Roadmap
Add SIEM detection rules
Expand ATT&CK mappings
Add timeline reconstruction
Improve alert-to-response automation
Integrate threat intelligence enrichment

👤 Author
Gustavo Okamoto
Cybersecurity Analyst | SOC / SIEM | Threat Detection & IR | Blue Team
Automation • Cloud Security • Incident Response
🔗 GitHub: https://github.com/gustavo89587
🔗 LinkedIn: https://linkedin.com/in/gustavo-okamoto-de-carvalho-ti

⭐ Star this repository if you value hands-on Blue Team work.