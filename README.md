# MohacWeb v3.0

Advanced Web Security Scanner with Deep Scan Engine

## Features

- **5-Layer Deep Scan**: Surface, Medium, Deep, Verification, Chain Analysis
- **SQL Injection Detection**: Error-based, Time-based blind
- **XSS Detection**: Reflected XSS with payload reflection
- **Sensitive Data Detection**: Emails, API keys, AWS keys, internal IPs
- **CSRF Token Check**: Missing CSRF token detection
- **Directory Brute Force**: 50+ common paths
- **PoC Generation**: Automatic proof-of-concept for each vulnerability
- **Chain Analysis**: RCE chains, data breach chains, auth bypass chains
- **HTML Reports**: Professional dark-theme reports with CVSS scores
- **SQLite Database**: All scan data stored locally

## Installation

```bash
unzip MohacWeb_v3.0.zip
cd MohacWeb_v3.0
bash install.sh
python3 MohacWeb.py
```

## Menu Options

1. Quick Scan - Fast scan with header/content/path analysis
2. Deep Scan - 5-layer comprehensive scan
9. Full Scan - Deep scan + report generation
12. Scan History - View past scans
13. Vulnerability Details - View detailed findings

## Requirements

- Python 3.7+
- No external dependencies required (uses stdlib)

## Disclaimer

For authorized security testing only. Always get permission before scanning.
