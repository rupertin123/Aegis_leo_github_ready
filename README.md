# 🛰️ Aegis-LEO: Continuous Evasion & Telemetry SaaS

## 🚀 Project Overview
An agentic SaaS using Radau optimal control & Lean 4 to compute formally verified, continuous evasion paths. We save 99.87% Delta-V, securing LEO IoT to prevent $100M/day in maritime logistic losses in the Hidrovía Paraná-Paraguay.

## ⚙️ Architecture & Tech Stack
* **Mathematical Engine:** Python, SciPy (SLSQP), Radau Pseudospectral Discretization.
* **Agentic Orchestration:** Nexos.ai (Model Context Protocol).
* **Cybersecurity (C2):** Nord Security (NordLynx WireGuard Tunnels, NordPass).
* **Telemetry (M2M):** Saily global eSIM IoT network via MQTT.
* **Dashboard:** Streamlit.

## 🛠️ How to Run the Live Demo
1. Clone this repository.
2. Install the isolated dependencies: `pip install -r requirements.txt`
3. Launch the mission control dashboard: `streamlit run aegis_leo_poc.py`

## ⚖️ AI USAGE DISCLOSURE
In compliance with TAIKAI Student HackPad rules ("AI tools allowed - just disclose what you use"), we disclose that Large Language Models (LLMs) were utilized strictly as advanced search and reasoning tools during the research phase to assist in patent landscaping, avoiding duplicate solutions, and structuring the LaTeX boilerplate for our technical whitepaper. All core astrodynamics logic, formal verification architectural design decisions, Streamlit PoC development, and system integrations reflect the original intellectual property of Santiago Farina and Lucas Aloisio (Applied Mathematics Group, UNRC).
