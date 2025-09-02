# CyberShield-AI-Suite

## Overview
CyberShield AI Suite is an integrated cybersecurity platform designed to detect, analyze, and mitigate digital threats using Artificial Intelligence. The suite combines three critical modules:
LLM-based Vulnerability Detection – Scans open-source software repositories to identify insecure code patterns and vulnerabilities.
Phishing Detection – Detects malicious emails, URLs, and messages using NLP and ML models.
Password Auditing & Recovery – Identifies weak passwords, performs ethical recovery of hashed credentials, and recommends stronger authentication practices.
This system aims to provide a comprehensive AI-driven shield against modern cyber threats, strengthening both organizational and national security.

## Problem Statements Addressed
- **PS-1:** LLMs to Detect Vulnerability in Open-Source Software
- **PS-2:** Phishing Detection
- **PS-7:** Password Extraction & Decryption (ethical auditing use case)

## Tech Stack  

- **Languages:** Python (ML/AI), JavaScript (Dashboard – React)  
- **Frameworks & Libraries:** PyTorch, TensorFlow, Hugging Face Transformers, Scikit-learn  
- **Web Backend:** Flask / Django  
- **Database:** PostgreSQL / MongoDB  
- **Security Tools:** Hashcat, John the Ripper (for password auditing)  
- **Deployment:** Docker, Kubernetes, Cloud (AWS/GCP/Azure)  


## Project Structure
 
```plaintext
CyberShield-AI-Suite/
├── data/                  # datasets (phishing, vulnerabilities, passwords)
├── notebooks/             # Jupyter notebooks for experiments
├── src/                   # source code for modules
│   ├── vuln_scanner/      # vulnerability detection
│   ├── phishing_detector/ # phishing detection
│   ├── password_auditor/  # password recovery
├── dashboard/             # frontend + backend web application
├── docs/                  # project documentation, abstract, reports
└── README.md
```

## Modules & Features
### Vulnerability Detection (PS-1)
Uses LLMs + static analysis to scan code repositories.
Flags common issues (buffer overflow, SQL injection, insecure API usage).
### Phishing Detection (PS-2)
Classifies emails/URLs as phishing or safe.
Uses NLP + ML classifiers on text and metadata.
### Password Auditing (PS-7)
Ethical password recovery for forensics.
Dictionary + rule-based password cracking.
Provides strength score + recommendations.

## Requirements
torch
tensorflow
transformers
scikit-learn
pandas
numpy
flask
requests
beautifulsoup4
these as requirement.txt

To install them, run:
```bash
pip install -r requirements.txt
```
## Roadmap  

- **Week 1:** Team setup, environment setup, dataset collection  
- **Week 2–3:** Build baseline models (vulnerability, phishing, password auditor)  
- **Week 4–5:** Integrate modules into unified dashboard  
- **Week 6+:** Optimize models, test, and deploy  


## Team Members
- **Divyansh** 
- **Sahil Aggarwal** 
- **kaki**
- **Tushar Khatri**
