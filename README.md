<div align="center">

<h1>🛡️ Cybersecurity Internship Portfolio</h1>

</div>


## Tasks Overview


### Task 1 — Network Sniffer (Flask + Scapy)
A real‑time packet sniffer with a polished cyberpunk UI and export tools.
- Features: live capture, filtering, search/sort, protocol/category stats, PCAP/CSV export, session login
  
### Task 2 — Phishing Awareness Training
Educational deliverables focused on phishing and social engineering.


### Task 3 — Secure Coding Review
Security audit and recommendations for safer software development.


### Task 4 — Network Intrusion Detection System (NIDS)
Custom Python NIDS plus Snort configs and visualization.


## Quick Start

### Windows — Task 1: Network Sniffer
Requires Administrator privileges for packet sniffing.

```powershell
# From repo root
cd "Task 1/Network Sniffer"

python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

# Run (as Administrator)
python app.py
# Then open http://localhost:5000 (default login: admin / admin123)
```

### Windows — Task 4: Python NIDS + Visualization
```powershell
# From repo root
cd "Task 4/Network Intrusion Detection System/python_nids"

python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

# Run NIDS (as Administrator)
python nids.py

# When finished, visualize alerts
cd ..\visualization
python dashboard.py
```

---

## Requirements
- Python 3.8+
- Windows/macOS/Linux (Admin/Root required for sniffing)
- Per‑task Python dependencies listed in each `requirements.txt`

---

## Repository Structure

```
Task 1/
  Network Sniffer/
    app.py, templates/, static/, requirements.txt, README.md
Task 2/
  Presentation - Phishing Awareness.(pdf|pptx)
Task 3/
  Documentation - Secure Coding Review.pdf
Task 4/
  Network Intrusion Detection System/
    python_nids/ (nids.py, requirements.txt, logs/)
    snort_config/ (snort.conf, local.rules)
    visualization/ (dashboard.py)
Tasks/
  Cyber Security Tasks & Instructions — CodeAlpha.pdf
LICENSE
```

---

## Disclaimer
This repository contains work completed for the CodeAlpha Cybersecurity Internship and is provided strictly for educational and demonstration purposes. Use packet capture, intrusion detection, and any security tooling only on systems and networks you own or have explicit, written permission to test. Ensure compliance with local laws, organizational policies, and internship guidelines at all times. The author assumes no responsibility for misuse.

---

## Author & License
- Author: Parth Panchal
