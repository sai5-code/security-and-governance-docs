# SecOps & Infrastructure Governance Mandate (v2.0 - Active Revision)

## 1. Encryption & Zero-Trust Architecture
- All customer PII data MUST be encrypted at rest using AES-256-GCM with automated KMS key rotation every 90 days.
- TLS 1.3 enforced across all public ingress endpoints and internal service mesh communication.

## 2. Production Deployment & Emergency Hotfix Protocol
- Standard production change freeze remains active Friday 16:00 UTC through Monday 06:00 UTC.
- **Emergency Exemption Rule (v2.0)**: Severity-1 security hotfixes (e.g. OAuth memory leaks) may be deployed during change freeze IF co-signed by VP of Engineering and 2 Senior SRE leads via Slack or Jira `SEC` ticket.

## 3. Incident SLA & Response Targets
- Severity-1 response time SLA target: 15 minutes.
