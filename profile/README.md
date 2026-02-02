<p align="center">
  <img src="https://github.com/Netshield-Enterprise/.github/blob/main/assets/netshield-logo.jpeg" width="100"/>
</p>

<h1 align="center">NetShield</h1>

[![GitHub Release](https://img.shields.io/github/v/release/Netshield-Enterprise/netshield-analyzer?style=flat-square)](https://github.com/Netshield-Enterprise/netshield-analyzer/releases)
[![Release Workflow](https://github.com/Netshield-Enterprise/netshield-analyzer/actions/workflows/release.yml/badge.svg)](https://github.com/Netshield-Enterprise/netshield-analyzer/actions/workflows/release.yml)
![Docker Pulls](https://img.shields.io/docker/pulls/ekene/netshield-analyzer)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](LICENSE)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-blue.svg)](./LICENSE-COMMERCIAL)
![Issues](https://img.shields.io/github/issues/Netshield-Enterprise/netshield-analyzer)
![Discussions](https://img.shields.io/github/discussions/Netshield-Enterprise/netshield-analyzer)

![Build](https://img.shields.io/github/actions/workflow/status/Netshield-Enterprise/netshield-action/build.yml?branch=main)
![Docker Pulls](https://img.shields.io/docker/pulls/ekene/netshield-action)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-blue.svg)](./LICENSE-COMMERCIAL)
![Issues](https://img.shields.io/github/issues/Netshield-Enterprise/netshield-action)
![Discussions](https://img.shields.io/github/discussions/Netshield-Enterprise/netshield-action)

## Real Risk Security for CI/CD Pipelines

Most security tools tell you vulnerabilities exist.  
NetShield tells you if attackers can actually use them in **your application**.

---

## Mission

Eliminate security noise.  
Block real risk.  
Let developers ship securely at high velocity.

---

## What Makes NetShield Different

Traditional tools answer:

> "Do vulnerabilities exist?"

NetShield answers:

> "Can this vulnerability actually be exploited in this release?"

NetShield is built for **CI/CD enforcement**, not vulnerability dashboards.

---

## Current Products

### netshield-analyzer

**Vulnerability Reachability & Real Risk Analysis**

Determines if vulnerable dependency code is actually reachable from application execution paths.

**Core Capabilities**
- Maven dependency analysis
- Java bytecode call graph construction
- CVE intelligence via OSV
- Reachability classification (REACHABLE / UNREACHABLE / UNKNOWN)
- Decision-focused release output
- CI/CD JSON output support

---

### netshield-action

**CI Secret Detection & Merge Enforcement**

Prevents credential leaks from reaching production.

**Core Capabilities**
- Pre-merge secret scanning
- Pull Request security comments
- Merge blocking enforcement
- Audit-friendly scan evidence

**Primary Use Case**
Stopping credential exposure before it reaches production or audit logs.

---

## Who NetShield Is For

- ✅ Fintech & regulated startups  
- ✅ SaaS companies shipping frequently  
- ✅ Teams without dedicated AppSec  
- ✅ Platform engineering teams  

---

## Not For

- ❌ Compliance checkbox tools  
- ❌ Security dashboard-only workflows  
- ❌ Manual review driven security models  

---

## Security Principles

- CI-first security enforcement  
- Deterministic analysis outputs  
- Developer-readable security decisions  
- Minimal required configuration  

---

## Long-Term Vision

NetShield is building toward:

- Exploitability-based release security  
- CI-native policy enforcement  
- Supply chain trust scoring  
- Autonomous security release decisions  

---

## Contributing

We welcome contributions in:

- Language ecosystem support  
- CI integrations  
- Performance optimization  
- Vulnerability intelligence enrichment  

---

## Community

Issues and discussions are open in individual repositories.

