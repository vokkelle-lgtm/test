# Vulnerability Scanner MVP

A minimal NIS2-compliant vulnerability scanner with REST API and web interface.

## Features

- Configurable Nmap-based vulnerability scanning
- CVE extraction and CVSS scoring
- NIS2 compliance reporting
- Sentinel.ai integration
- Docker containerization
- REST API with OpenAPI documentation

## Quick Start

```bash
git clone https://github.com/vokkelle-lgtm/vuln-scanner-mvp.git
cd vuln-scanner-mvp
cp .env.example .env
# Edit .env with your Sentinel.ai API key
docker-compose up --build -d