# soc-ai-soar-platform
This project simulates a real-world Security Operations Center (SOC) pipeline that detects, analyzes, and responds to security threats automatically.  It integrates SIEM, threat intelligence, AI-based triage, and automated response into a single system.

⚙️ Features
- Wazuh SIEM integration
- IOC extraction
- Threat intelligence using VirusTotal & AbuseIPDB
- AI based alert analysis using local LLM (Ollama) gemma 4
- Automated response for IP blocking
- Telegram bot alerts for notification

🧠 Architecture
Wazuh → Python SOAR → Threat Intel → AI → Response

🛠️ Tech Stack
- Python
- Wazuh SIEM
- Streamlit
- Ollama (LLM) Gemma 4
- iptables
- Telegram Bot API

🚀 How It Works
1. Wazuh detects suspicious activity
2. Python script extracts IOC (IP)
3. Threat intelligence APIs enrich the data
4. AI analyzes severity and suggests action
5. System automatically blocks malicious IP
6. Telegram alert is sent

