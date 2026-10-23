# Addison Smith

Controls Application Engineer at Mantis Innovation. I work where building automation meets applied AI.

Industrial automation taught me how things actually break. Most of what I build here comes out of that: tooling for the OT data plane, and AI that assists an engineer without ever touching the building.

## OT data infrastructure

| Project | What it does |
|---|---|
| [ot-stack](https://github.com/AddisonTech/ot-stack) | One-command Compose demo of the data plane: mosquitto → Iris → Clio |
| [Hermes](https://github.com/AddisonTech/Hermes) | OPC-UA bridge and MCP server for AI agent access to plant-floor data (Rust) |
| [Iris](https://github.com/AddisonTech/Iris) | MQTT/Sparkplug bridge — subscribe, expose via REST + MCP, forward to a historian |
| [Clio](https://github.com/AddisonTech/Clio) | Zero-infra SQLite time-series historian for the OT stack |
| [ModBridge](https://github.com/AddisonTech/ModBridge) | Modbus TCP collector in Rust — live polling, CSV logging, REST API |
| [Mnemosyne](https://github.com/AddisonTech/Mnemosyne) | Immutable Modbus register ledger; every poll hashed into a tamper-evident chain |
| [Niagara_MCP](https://github.com/AddisonTech/Niagara_MCP) | Read-only MCP server for Tridium Niagara stations: AI access to points, alarms, and history, with no write path |

## Applied AI for controls

| Project | What it does |
|---|---|
| [bms-alarm-triage-agent](https://github.com/AddisonTech/bms-alarm-triage-agent) | Turns a raw BMS alarm queue into a short ranked list of what to look at first. ANSI/ISA-18.2 classification, deterministic core, LLM only at the explanation step |
| [Hyperbolic](https://github.com/AddisonTech/Hyperbolic) | AI supervisor on a simulated building district that tries to beat the stock control sequence on cost, emissions, and comfort. Deterministic safety envelope on every action. [Replay viewer](https://addisontech.github.io/Hyperbolic/) |
| [Argus](https://github.com/AddisonTech/Argus) | Watches live Modbus registers for anomalies and explains them in plain English |
| [Vision_Inspect](https://github.com/AddisonTech/Vision_Inspect) | Local VLM visual inspection — defect detection, OCR, anomaly classification |
| [Smith_Agentic](https://github.com/AddisonTech/Smith_Agentic) | Local multi-agent system on CrewAI + Ollama. No cloud dependencies |

## Background

Vertiv → AIRSYS → Daedalus Industrial → Mantis Innovation. Switchgear wiring to controls application engineering. Rockwell Studio 5000, FactoryTalk View, Ignition, Niagara, BACnet/Modbus. Ignition Gold certified. Finishing a BS in IT (AI/ML and Data Analytics) at ECPI, February 2027.

[Portfolio](https://addisontech.github.io) · [LinkedIn](https://linkedin.com/in/addison-smith-tech) · [Blog](https://addisonsmithdev.wordpress.com)
