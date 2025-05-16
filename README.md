# All Custom Nuclei Templates by RamahProgrammer

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Last Updated](https://img.shields.io/github/last-commit/RamahProgrammer/All-custom-Nuclei-templates)
![Templates](https://img.shields.io/badge/Nuclei-Templates-blueviolet)
![Made with](https://img.shields.io/badge/Made%20with-Nuclei%20%26%20Recon-ff69b4)

This repository contains custom Nuclei templates for advanced API and web recon testing.

## 📌 Templates Included

### 🔐 API Security
- `graphql-introspection.yaml` – Detect GraphQL introspection exposure
- `rate-limit-bypass.yaml` – Test for rate limit bypass
- `openapi-docs-exposed.yaml` – Detect exposed Swagger/OpenAPI documentation
- `jwt-auth-bypass.yaml` – Check for JWT authentication flaws
- `bola-user-id-enumeration.yaml` – Test for BOLA (Broken Object Level Authorization)
- `openapi-param-fuzz.yaml` – Fuzz OpenAPI parameters for misconfigurations

### 🕵️ Advanced Recon
- `tech-stack-fingerprint.yaml` – Fingerprint tech stack via HTTP headers
- `admin-panel-finder.yaml` – Identify common admin panel paths
- `cloud-metadata-leak.yaml` – Detect exposed cloud metadata endpoints (AWS, Azure, GCP)
- `open-redirect-check.yaml` – Identify open redirect vulnerabilities
- `cors-misconfig.yaml` – Detect CORS misconfigurations

---

## 🚀 Usage

```bash
nuclei -u https://target.com -t ./templates/
