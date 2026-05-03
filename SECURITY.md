# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this repository, please report it
privately so the issue can be triaged and remediated before public disclosure.

**Contact:** jason.pereira@woodgate.com
**Subject line:** `SECURITY: <repository-name> — <short summary>`

Please include:

- A description of the vulnerability and the potential impact
- Steps to reproduce (proof-of-concept code, request payloads, or screenshots)
- The affected version, commit SHA, or deployment URL
- Your name and a preferred contact method for follow-up (optional — anonymous
  reports are accepted)

You will receive an acknowledgement within **2 business days**. A remediation
plan or status update will follow within **10 business days** of acknowledgement.

## Disclosure Policy

Woodgate Financial follows coordinated responsible disclosure:

1. Reporter submits a private report via the contact above.
2. Maintainer acknowledges receipt and begins investigation.
3. Maintainer and reporter agree on a remediation timeline.
4. Fix is developed, tested, and deployed.
5. Public disclosure (advisory, CVE, or release notes) is published after the
   fix is live, crediting the reporter unless anonymity is requested.

Please **do not** open public GitHub issues, pull requests, or discussions for
suspected vulnerabilities. Public disclosure before remediation puts users at
risk and is not consistent with responsible disclosure practice.

## Scope

This policy covers the source code in this repository and any deployment
operated by Woodgate Financial that is built from it. Out of scope:

- Vulnerabilities in third-party dependencies for which an upstream advisory
  already exists (please report those upstream)
- Social-engineering or physical-security attacks against Woodgate Financial
  staff
- Denial-of-service testing against production systems

## Compliance Context

Woodgate Financial is a Canadian financial advisory firm. Reports involving
client personal information, financial data, or regulated workflows are handled
in accordance with:

- **PIPEDA** — Personal Information Protection and Electronic Documents Act
- **FinTRAC** — Financial Transactions and Reports Analysis Centre of Canada
  obligations
- Applicable **Canadian securities regulation** (CIRO / CSA)

Reports that may involve a notifiable privacy breach will be escalated to the
firm's Privacy Officer.

## Safe Harbour

Woodgate Financial will not pursue legal action against researchers who:

- Make a good-faith effort to follow this disclosure policy
- Avoid privacy violations, destruction of data, or service disruption
- Do not access, modify, or exfiltrate data beyond what is necessary to
  demonstrate the vulnerability
- Give the firm a reasonable opportunity to remediate before public disclosure

---

*Last updated: 2026-05-03*
