🔵 Blue Team Labs
Logs reais | Investigação SOC | Ameaças simuladas

Este repositório contém uma coleção de labs práticos pensados para treinar habilidades de:

Análise de logs

Detecção de anomalias

Investigação SOC Tier 1 / Tier 2

Raciocínio de Threat Hunting

Resposta a incidentes

Todos os labs usam dados reais simulados, cobrindo cenários comuns de segurança.

🎯 Objetivos

✔ Treinar investigação em logs Linux, DNS e Windows
✔ Criar raciocínio de detecção baseado em comportamento
✔ Simular incidents reais (brute force, exfiltração, persistência)
✔ Desenvolver maturidade SOC escolhida por recrutadores
✔ Servir de portfólio técnico profissional

📁 Estrutura do Repositório
blue-team-labs/
│
├── logs/
│   ├── linux_auth.log
│   ├── dns.log
│   └── windows.json
│
├── labs/
│   └── brute_force/
│       ├── challenge.md
│       └── hints.txt
│
└── answers/
    └── brute_force.md

🧪 Conteúdo dos Labs
1. Brute Force – Linux Auth Logs

Neste desafio, o analista deve identificar:

Tentativas repetidas de login

IPs suspeitos

Contas alvo

Indicadores de brute force

Padrões anômalos

O arquivo answers/brute_force.md oferece uma explicação técnica de como a investigação deve ser feita.

2. DNS Logs

Exercício ideal para treinar:

Domínios raros

Consultas suspeitas

Volume anômalo

Possíveis tunneling attempts

3. Windows Logs

Dataset base para futuras análises, incluindo:

Execuções suspeitas

Processos incomuns

Eventos críticos

▶️ Como Usar

Abra os arquivos de log, analise os eventos e tente identificar:

✔ Anomalias
✔ Indicadores de ataque
✔ Padrões de comportamento
✔ Possíveis TTPs

Depois, compare com a resposta em /answers/.

🛡️ Habilidades Demonstradas com Este Repositório

Investigação SOC

Threat Hunting em logs

Análise de Linux Auth, DNS e Windows

Detecção comportamental

Documentação técnica e metodologias Blue Team

MITRE ATT&CK

📬 Contato

Gustavo Okamoto
Cybersecurity Analyst – SOC | Threat Detection
📧 gugaokamoto1@gmail.com

🔗 linkedin.com/in/gustavo-okamoto-de-carvalho-ti
🔗 github.com/gustavo89587
