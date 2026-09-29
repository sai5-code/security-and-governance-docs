# SecOps & Infrastructure Governance Mandate (v1.0 - Active Legacy)

## 1. Data Protection & Encryption
- All customer PII data MUST be encrypted at rest using AES-256-GCM.
- TLS 1.3 is strictly enforced for all public API endpoints.

## 2. Production Deployment Change Freeze
- Production change freezes are active every Friday after 16:00 UTC.
- NO deployments permitted on Friday after 16:00 UTC without written authorization signed by CCO and VP of Engineering.

## 3. Audit Retention
- Audit logs must be retained for 365 days in immutable storage.
