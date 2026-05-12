# Security Policy

## Reporting a Vulnerability

This repository is maintained by an **individual maintainer on a best-effort basis**. There is no formal SLA, but security reports are taken seriously and prioritized.

### How to Report

**Please use [GitHub Security Advisories](../../security/advisories/new)** to report vulnerabilities privately.

Do **not** open public issues for security vulnerabilities.

### What to Include

- Affected version / commit SHA
- Reproduction steps or proof-of-concept
- Impact assessment (data exposure, RCE, DoS, etc.)
- Suggested mitigation if known

### Response Expectations

- **Initial acknowledgement**: within 7 days (best-effort)
- **Triage and assessment**: within 14 days
- **Fix or mitigation timeline**: communicated case-by-case

This is a personal/individual project. Responses may be delayed during travel, personal time, or other commitments. For urgent issues, please indicate severity in the advisory title.

### Scope

In scope:
- Vulnerabilities in this repository's code
- Vulnerable dependencies that can be exploited via this project
- Misconfigurations in CI/CD workflows shipped in this repo

Out of scope:
- Issues in upstream dependencies (please report to the upstream project)
- Social engineering, physical attacks, or attacks requiring privileged access
- Best-practice deviations without demonstrated exploitability

### Disclosure Policy

Coordinated disclosure is preferred. Once a fix is published, the reporter is invited (but not required) to be credited in the advisory.

---

*This SECURITY.md follows the [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories) workflow. Last updated: 2026-05-12.*
